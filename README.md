wak-freexl
==========

Wakanda module to use FreeXL

Example
-------
Run the project, open index.html and drag and drop an XLS file.

![](https://github.com/miyako/wak-freexl/blob/master/images/screenshot.png)

```js
var modulesFolder = FileSystemSync('Modules');
var xl = require(modulesFolder.path + 'xl');

var path = getFolder().path + 'Documents/tester1.xls'

xl.toSQL(path);
```
