# mdEditor User Manual

## Overview

The mdEditor is a web application that allows users to author and edit metadata for projects and datasets. The primary design goal was to develop an editor that would allow someone to create and use archival quality metadata without the need for an extensive knowledge of metadata standards. More....

## Features

An introductory blurb....

* Responsive, two-panel layout should allow display on desktop and mobile devices
* Launched through a web browser, no need to install software
* Metadata stored locally
* Metadata can be exported as a text file \(JSON format\) for archiving or sharing
* Open source development allows for customization
* Defined schema \(mdJSON schema\) allows for validating records
* Can be used in conjunction with an associated [mdTranslator](https://github.com/adiwg/mdTranslator) application to create ISO and FGDC compliant metadata records.

## Development history

ADIwg hstory.....

Primary development has been performed by Josh Bradley \(joshua\_bradley@fws.gov\) and Stan Smith \(ssmith@arcticlcc.org\) of the [Arctic Landscape Conservation Cooperative](http://arcticlcc.org/).

## Basic Navigation

The mdEditor application is designed using a two-pane layout. The left [_**sidebar**_](#sidebar) \(1\) provides the primary navigation showing a list of [metadata records](/records.md), [contacts](/contacts.md) and [data dictionaries](/dictionaries.md). The right pane displays a context-sensitive [_**main menu**_](#main-menu) at the top \(2\) and a primary [_**editor region**_](#editor-region) below \(3\) that displays and allows for the editing of a selected object.

![](/assets/mdEditor_areas.png)

### Sidebar

The left sidebar displays the various components of the current metadata record set. The components are arranged by type in a series of expandable object group panels.

![](/assets/mdEditor_logo_32.png)   Select the **mdEditor **logo to toggle the display of the sidebar.

![](/assets/symbol_question-circle_16.png) Select the **help icon** to display context-sensitive help. Click again to view the object groups.

![](/assets/symbol_plus_16.png) Select the **plus icon **to add a new record to an object group.

![](/assets/symbol_list_16.png) Select the **list icon** to display a list of individual objects in the editor region.

![](/assets/symbol_angle-down_16.png) Select the **angle-down icon** to expand an object group panel and display a list of objects in the sidebar.

![](/assets/symbol_angle-up_16.png) **angle-up icon**. Collapse an object panel to hide all associated objects.

### Main menu

The main menu contains several standard menu items that apply to areas of the mdEditor and content-specific menu items that will vary depending upon the type of record that is active.

#### Standard menu items

The following standard menu items will always be displayed on the  main menu.

![](/assets/symbol_dashboard_16.png) **Dashboard**. Return to main dashboard. See [Dashboard](/dashboard.md).

![](/assets/symbol_sign-out_16.png) **Export**. Export metadata records in mdJSON format. The mdJSON file can be used to share your metadata with others or to provide a backup. [See Export](/export.md).

![](/assets/symbol_sign-in_16.png) **Import**. Import a mdJSON file into the editor. [See Import](/import.md).

![](/assets/symbol_cog_16.png) **Settings**. Customize the editor settings. [See Settings](/settings.md).

### Editor region

The editor region will display information based on the type of object that is currently selected. Selecting a **list icon** \(![](/assets/symbol_list_16.png)\)will display all of the the records contained in the associated object \(metadata, contacts or dictionaries\) in the editor region. Selecting a record will display record specific information and allow the record to be edited.

