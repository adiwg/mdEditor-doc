# Appendix 2: Documentation Authoring Guide

---

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [About this guide](#about-this-guide)
	- [Who is this guide for?](#who-is-this-guide-for)
	- [What is it about?](#what-is-it-about)
- [Workflow](#workflow)
	- [Setup Environment](#setup-environment)
	- [Contributing using GitHub](#contributing-using-github)
- [Style Guide](#style-guide)
	- [Headings](#headings)
	- [Lists](#lists)
		- [Ordered lists](#ordered-lists)
		- [List headings](#list-headings)
	- [Icons](#icons)
	- [Buttons](#buttons)
	- [Hints](#hints)
	- [User Interface Elements](#user-interface-elements)
	- [Screenshots](#screenshots)
		- [Types of screenshots](#types-of-screenshots)
		- [Requirements for all screenshots](#requirements-for-all-screenshots)
		- [Requirements for annotated screenshots](#requirements-for-annotated-screenshots)
		- [Screenshot captions](#screenshot-captions)
		- [Bookmarlet for Screenshots](#bookmarlet-for-screenshots)

<!-- /TOC -->

## About this guide

---

### Who is this guide for?

This guide is intended for parties interested in contributing to this documentation.

### What is it about?

This guide describes a recommended workflow and required conventions to be used
when creating content.

## Workflow

---

### Setup Environment

While the online editor may be used, the most efficient way to create
documentation is to install the GitBook Toolchain locally. See
https://toolchain.gitbook.com/ for detailed instructions. The short version
follows.

{% hint style='info' %}

The following is required:
 * NodeJS (v4.0.0 and above is recommended)
 * git
 * A Markdown editor/IDE ([ATOM](https://atom.io/) is a good open source choice)
 * Windows, Linux, Unix, or Mac OS X
{% endhint %}


1. Install `gitbook-cli` using npm:

    ```bash
    $ npm install gitbook-cli -g
    ```

1. Clone the mdEditor GitBook:

    ```bash
    $ git clone git@github.com:adiwg/mdEditor-doc.git
    ```
    or
    ```bash
    $ git clone https://github.com/adiwg/mdEditor-doc.git
    ```
1. Setup GitBook

    ```bash
    $ cd mdEditor-doc
    $ gitbook install
    ```
1. Start the local GitBook server

    ```bash
    $ gitbook serve
    ```
1. Open a browser to: http://localhost:4000

### Contributing using GitHub

Fork this repository (click "fork" on the
[repository's home page](https://github.com/adiwg/mdEditor-doc) in GitHub)

Clone the forked repository with `git clone <your fork's url>` and create a
branch with `git checkout -b some-branch-name`.

As you make commits, reference the issue number, if any, in your commit message, such as
`git commit -m "added information on important subject (#62)"`

Once you're at the point that you'd like feedback, submit a Pull Request (new
Pull Request button). Choose `master` for the base and your branch name for `compare`,
then submit it!

Your PR will be reviewed by another contributor, and then either merged or have
changes requested.

## Style Guide

---

This section covers styling conventions required for this documentations. Some of
the conventions rely on plug-ins that enhance the native GitBook Markdown functionality.
In some instances, the effects of the plugins are not displayed until after the
book has been generated.

### Headings

Please use headings to define page sections. Heading levels should appear
sequentially without gaps (don't skip heading levels). Headings should start at
Level 1 for the page title. Headings should not be used purely to define font
styles - if absolutely necessary, use CSS for that. Following this convention
will make it possible to parse the markdown  programmatically, e.g. to
dynamically create a table of contents.

### Lists

#### Ordered lists

Ordered lists are processed irrespective of the actual number assigned to each list item.
For Example:

```
1. first
2. second
3. third
```

{% hint style='plain' %}
1. first
2. second
3. third
{% endhint %}

is rendered the same as:
```
1. first
12. twelfth
30. thirtieth
```

{% hint style='plain' %}
1. first
12. twelfth
30. thirtieth
{% endhint %}

Therefore, one recommended convention is to use `1.` for every item in an ordered
list. This makes it easier to insert or remove items from the list, at the
expense of slightly less readable Markdown. If you choose to sequentially order
the list items, you **must** make sure the numbers are sequential to avoid confusion.

#### List headings

Headings may be use in lists. However, special handling is required to ensure
bullets for ordered lists are styled appropriately.

The `tasks` tag is available for styling "task lists". For simplicity, all of the various heading levels are styled the same.

```markdown
Example without task tag

1. ## Level 2
1. ### Level 3
1. ###### Level 6
```

{% hint style='plain' %}

Example without task tag

1. ## Level 2
1. ### Level 3
1. ###### Level 6

{% endhint %}


```
Example with task tag

<!-- tasks -->
1. ## Level 2
1. ### Level 3
1. ###### Level 6
<!-- endtasks -->
```

{% hint style='plain' %}

Example with task tag

<!-- tasks -->
1. ## Level 2
1. ### Level 3
1. ###### Level 6
<!-- endtasks -->

{% endhint %}

### Icons

[FontAwesome](https://fontawesome.com/v4.7.0/icons/) icons are available. Use an
`<i>` tag to render the chosen icon.

```
<i class="fa fa-smile-o"> </i> Happy Birthday <i class="fa fa-birthday-cake"> </i>
```

{% hint style='plain' %}

<i class="fa fa-smile-o"> </i> Happy Birthday <i class="fa fa-birthday-cake"> </i>

{% endhint %}

### Buttons

[Bootstrap 3](https://getbootstrap.com/docs/3.3/css/#buttons) style buttons are supported. Use a `<span>` tag since these are
for documentation only. Icons may be combined with buttons.

<span class="btn btn-default">Default</span>
<span class="btn btn-primary">Primary</span>
<span class="btn btn-success"><i class="fa fa-check"> </i> Success</span>
<span class="btn btn-info btn-xs">Info Extra - Small</span>
<span class="btn btn-warning btn-sm">Warning - Small</span>
<span class="btn btn-danger btn-lg">Danger - Large</span>
<span class="btn btn-link">Link</span>

```html
<!-- Standard button -->
<span class="btn btn-default">Default</span>

<!-- Provides extra visual weight and identifies the primary action in a set of buttons -->
<span class="btn btn-primary">Primary</span>

<!-- Indicates a successful or positive action -->
<span class="btn btn-success"><i class="fa fa-check"> </i> Success</span>

<!-- Contextual button for informational alert messages -->
<span class="btn btn-info btn-xs">Info Extra - Small</span>

<!-- Indicates caution should be taken with this action -->
<span class="btn btn-warning btn-sm">Warning - Small</span>

<!-- Indicates a dangerous or potentially negative action -->
<span class="btn btn-danger btn-lg">Danger - Large</span>

<!-- Deemphasize a button by making it look like a link while maintaining button behavior -->
<span class="btn btn-link">Link</span>
```

### Hints

Styled hint blocks are supported.

```markdown
{% hint style='info' %}
Important info: this note needs to be highlighted
{% endhint %}
```

There are five supported variations.

- `info` (default)
- `tip`
- `danger`
- `working`
- `plain`

{% hint style='info' %}
Info: this note needs to be highlighted.
{% endhint %}

{% hint style='tip' %}
Tip: 20% is customary.
{% endhint %}

{% hint style='danger' %}
Danger: this is going to blow up!
{% endhint %}

{% hint style='working' %}
Working: for the man every night and day...
{% endhint %}

{% hint style='plain' %}
Plain: booooooorrrrring.
{% endhint %}

### User Interface Elements
 The following classes may be used to highlight text that refers to elements of
the user interface:
 ```html
<span class="md-window">window</span>
<span class="md-section">section</span>
<span class="md-panel">panel</span>
<span class="md-element">element</span>
```
<span class="md-window">Window Part</span>
<span class="md-section">Edit Window Section</span>
<span class="md-panel">Panel Name</span>
<span class="md-element">panel element</span>

### Screenshots

{% hint style='info' %}

The following software is required:
 * [Libre Office Draw](https://www.libreoffice.org/)
 * A tool to capture screenshots
 * Windows, Linux, Unix, or Mac OS X

{% endhint %}

#### Types of screenshots

  1. *basic* screenshots have no annotation or markup applied
  1. *annotated* screenshots have markup applied, e.g. callouts, highlights, etc.


#### Requirements for all screenshots

  1. Minimum 1200px wide
  1. Must include a caption
  1. PNG format
  1. Generally browser window captures should only contain minimum user interface
  controls, without navigation toolbar, tab bar, bookmarks toolbar, or status
  bar. See [Bookmarlet for Screenshots](#bookmarlet-for-screenshots).

    ![Example browser screenshot.](/assets/get-started/homepage.png){caption class=border}

  1. Images should be stored in the `assets` directory corresponding to the
  section in which the image appears. Exceptions to this requirement are made
  for images used in multiple sections.
  1. Image sizes should be as small as possible without sacrificing quality.
  Usually significant size reduction can be achieved by color-type or bit-depth
  reduction. [pngcrush](https://en.wikipedia.org/wiki/Pngcrush) is a good tool for this.

#### Requirements for annotated screenshots
  1. Use LibreOffice Draw to create the annotations
    * A template is available here `/assets/documentation-guide/callouts-template.odg`
    * Each screenshot should be placed on a new page
    * Whenever possible place annotations in callouts *outside* of the image or in a way that  does not cover user interface elements
    * Export only the image by
      * selecting all content on the LibreOffice Draw page using cntl-A
      * choose 'Export ...' from the file menu
      * select 'PNG' from the 'Format' drop-down selection list
      * check the 'Selection' box on the Export window
      * click the 'Save' button
      * set the pixels width to 1200
      * choose a compression level  of 6
      * click the 'OK' button
  1. All annotated screenshots for a section should be stored on separate pages in a single `.odg` file.
  1. Save the LibreOffice Draw file (.odg) in the same directory as the screenshots

  ![Creating screenshots using LibreOffice Draw](/assets/documentation-guide/libreoffice-screenshot.gif){caption class=border}

#### Screenshot captions

To apply a caption to a screenshot use this syntax in the Markdown.

```markdown
![caption goes here](/assets/path/to/image){caption}
```
![Screenshot with caption](/assets/documentation-guide/example-image.png){caption}

To apply a border to a screenshot, add `class=border`.

```markdown
![caption goes here](/assets/path/to/image){caption class=border}
```
![Screenshot with border](/assets/documentation-guide/example-image.png){caption class=border}

Applying the `{caption}` to a image will also indent the image from the surrounding text.

#### Bookmarlet for Screenshots

Use this bookmarlet: <a href="javascript:(function(){var windowObjectReference;var strWindowFeatures='menubar=no,location=yes,resizable=yes,scrollbars=yes,status=no,width=1200,height=1200';windowObjectReference=window.open(window.location.href,'Plain Jane',strWindowFeatures);})();">Plain Window</a>. Drag the link to your bookmarks bar or create a bookmark with the code below. Clicking the bookmark will open the current webpage in a plain window that is 1200px wide. Re-size to needed height and take a screenshot. More about bookmarlets here: https://www.wikipedia.org/wiki/Bookmarklet.

```javascript
javascript:(function(){var windowObjectReference;var strWindowFeatures='menubar=no,location=yes,resizable=yes,scrollbars=yes,status=no,width=1200,height=1200';windowObjectReference=window.open(window.location.href,'Plain Window',strWindowFeatures);})();
```
