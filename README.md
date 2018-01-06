# mdEditor User Manual

## Overview

The mdEditor is a web application that allows users to author and edit metadata for projects, datasets, maps, images, and documents. The primary design goal was to develop an application that would allow someone to create and use archival quality metadata without the need for an extensive knowledge of metadata standards.

## Features

* Responsive, two-panel layout should allow display on desktop and mobile devices.
* Launched through a web browser, no need to install software.
* Metadata is initially stored in the browser local storage cache.
* Metadata can be exported as a text file \(JSON format\) for archiving or sharing.
* Open source development allows for customization.
* Defined schema \(mdJSON schema\) allows for validating records.
* Can be used in conjunction with an associated [mdTranslator](https://github.com/adiwg/mdTranslator) application to create ISO and FGDC compliant metadata records.

## Background

The mdEditor is an extension of a project initiated by the [Alaska Data Integration Working Group](http://www.adiwg.org/about/) \(ADIwg\) to adopt a set of project-level metadata fields for use by [member organizations](http://www.adiwg.org/about/#contributing-organizations). This editor is one of several integrated ADIwg projects, which include an ADIwg developed [mdJSON Schema](https://github.com/adiwg/mdJson-schemas) that forms the underlying data structure for metadata records and a [variety of tools](http://mdtools.adiwg.org/#popup-welcome) that allow the mdJSON data file to be validated against the mdJSON schema and converted to other formats.

The mdEditor is a web application for authoring and editing metadata, for both projects and datasets. It interfaces with the mdTranslator to convert mdJSON to other metadata formats.

mdEditor has the ability to:

* Create mdJSON which is compatible with mdTranslator.
* Manage multiple records at once.
* Re-use metadata records, contacts, and dictionaries.
* Support spatial extents \(which are imported or drawn using the editor\).
* Import/Export managing record "sets" on the local filesystem.
* Use built-in keyword thesaurus or create custom keyword lists.

Primary development has been performed by Josh Bradley \(joshua\_bradley@fws.gov\) and Stan Smith \(ssmith@arcticlcc.org\) of the [Arctic Landscape Conservation Cooperative](http://arcticlcc.org/).

