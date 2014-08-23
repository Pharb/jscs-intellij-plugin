# jscs support plugin for Intellij IDEsk (PREVIEW)
Interactive live-check using jscs of the JavaScript file you are currently viewing or working on.
## Supported environments:
* Only Linux operating systems are currently supported (tested only on Ubuntu based systems)

* Tested IDEs:
 * IntelliJ IDEA Ultimate 13.1 and higher, PyCharm Ultimate 3.1 and higher
* Untested, but should be working:
 * WebStorm 7 and higher, PhpStorm 7 and higher


## Getting Started

(_This will change in a future version_)

You have to install the latest [developer version of jscs](https://github.com/mdevils/node-jscs) globally to use this plugin currently:

```sudo npm install -g mdevils/node-jscs```

* Make sure .jscsrc is in the project root directory!

* Currently you have to install this plugin manually: 

 * Download newest version from the __dist__ directory
 * Open _Settings_ 
 * Go to _Plugins_
 * Select _Install_ _plugin_ _from_ _disk..._
 * Choose the downloaded __jscsPluginSupport-< VERSION >.jar__ file
 * Restart your IDE

## Support
**Feel free to test this alpha preview and use the issue tracker for feedback.**


## License
This project is licensed under the MIT License. See [LICENSE](https://github.com/Pharb/jscs-intellij-plugin/blob/master/LICENSE).


* This was inspired by: [idok/eslint-plugin](https://github.com/idok/eslint-plugin)