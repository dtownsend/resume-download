resume-download
================


`<resume-download>` is a part of a suite of web components that when combined create a full resume into a single web component tag.

`<resume-download>` adds a user defined image and destenation for people to download the users email.

## Getting Started


1. Import Polymer

  ```html
  <script src="bower_components/platform/platform.js"></script>
  ```

2. Import resume-download

  ```html
  <link rel="import" href="elements/resume-download.html">
  ```
  
3. call resume-download

  ```html
  <resume-download></resume-download>
  ```
  
Attributes
===========

| Attributes       | syntax           | description  |
| ------------- |:-------------:| -----:|
| download      | `dwn` | location of users resume for people to download |
| name      | `nm`      | name of the resume file |
| image | `img`      |    image the user uses to repersent there resume |
| description| `dis`      | hover over description |
| width | `w`      | overrides the default width of the image |
| height | `h`      | overrides the default height of the image |

