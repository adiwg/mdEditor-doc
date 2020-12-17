### Online Transfer Option 

![Online Transfer Option Edit Window](/assets/reference/edit-objects/metadata/distribution/OnlineTransferOption.PNG)

---

- **Name:** *{**type**: string; **max length**: none; **default**: empty}
  Usage:* The name of the online resource.

- **URI:** *{**type**: [URI](https://guide.mdeditor.org/GLOSSARY.html#uri); **default**: empty}
  Usage: * The internet location (address) for online access to the resource using the [URI](https://guide.mdeditor.org/GLOSSARY.html#uri) format - a.k.a URL.

- **Protocol:**  *{**type**: string; **max length**: none; **default**: empty}
  Usage:* The online connection protocol used to access the resource. e.g. ftp, http, https, etc.

- **Description:** *{**type**: string; **max length**: 500 characters; **default**: empty}
  Usage:* A text description with additional details of what the resource is or describes.

- **Function:** *{**type**: codelist (ISO CI_OnLineFunctionCode, [ADIwg](https://guide.mdeditor.org/GLOSSARY.html#adiwg) codes); **extensible**: YES; **multi-value**: NO; **default**: empty} Usage:* - A code declaring the intended function of the resource.

- **Application Profile:** The name of an application profile that can be used with the online resource

- **Protocol Request:** The request used to access the resource depending on the protocol (to be used mainly for POST requests)
