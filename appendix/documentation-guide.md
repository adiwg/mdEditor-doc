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

    ```
    $ npm install gitbook-cli -g
    ```

1. Clone the mdEditor GitBook:

    ```
    $ git clone git@github.com:adiwg/mdEditor-doc.git
    ```
    or
    ```
    $ git clone https://github.com/adiwg/mdEditor-doc.git
    ```
1. Setup GitBook
    ```
    $ cd mdEditor-doc
    $ gitbook install
    ```
1. Start the local GitBook server
    ```
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
    * A template is avaiable here `/assets/documentation-guide/callouts-template.odg`
    * Each screenshot should be placed on a new page
    * Whenever possible place annotations in callouts *outside* of the image or
    in a way that  does not cover user interface elements
    * Name the page using the name of the PNG file
    * Export the screenshot to PNG
      * only export the
      * compression level 6
      * 1200 pixels wide
  1. All annotated screenshots for a section should be stored in a single `.odg` file.
  1. Save the LibreOffice Draw file (.odg) in the directory with the screenshots

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

Use this bookmarlet: <a href="javascript:(function(){var windowObjectReference;var strWindowFeatures='menubar=no,location=yes,resizable=yes,scrollbars=yes,status=no,width=1200,height=1200';windowObjectReference=window.open(window.location.href,'Plain Jane',strWindowFeatures);})();">Plain Window</a>. Drag the link to your bookmarks bar or create a bookmark with the code below. Clicking the bookmark will open the current webpage in a plain window that is 1200px wide. RE-size to needed height and tkae a screenshot. More about bookmarlets here: https://www.wikipedia.org/wiki/Bookmarklet.

```javascript
javascript:(function(){var windowObjectReference;var strWindowFeatures='menubar=no,location=yes,resizable=yes,scrollbars=yes,status=no,width=1200,height=1200';windowObjectReference=window.open(window.location.href,'Plain Window',strWindowFeatures);})();
```
