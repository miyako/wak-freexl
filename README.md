wak-freexl
==========

Wakanda module to use [FreeXL](https://www.gaia-gis.it/fossil/freexl/index).

* libjson/7.6.1
* libiconv/1.14
* libfreexl/1.0.0g/h

Mac OS X, Windows x64, Linux x64

![obsolete-word-black-frame-word-obsolete-word-black-frame-d-rendering-123942590](https://user-images.githubusercontent.com/1725068/78463940-29122280-771e-11ea-8be8-a7830725403e.jpg)

Old Wakanda.

Example
-------
Run the project, open index.html, drag and drop an XLS document.

![](https://github.com/miyako/wak-freexl/blob/master/images/screenshot.png)

```js
var modulesFolder = FileSystemSync('Modules');
var xl = require(modulesFolder.path + 'xl');

var path = getFolder().path + 'Documents/tester1.xls'

xl.toSQL(path);
```
XLS To JSON
-----------
![](https://github.com/miyako/wak-freexl/blob/master/images/tojson.png)

Source repository is [here](https://github.com/miyako/console-xml-to-json).
