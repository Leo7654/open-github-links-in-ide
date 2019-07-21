# Chrome extension to open GitHub file links in your IDE

[![CircleCI](https://circleci.com/gh/lmichelin/open-github-links-in-ide.svg?style=svg)](https://circleci.com/gh/lmichelin/open-github-links-in-ide)

This browser extension allows you to open files in your IDE directly from GitHub with the cursor at the desired line when possible.

<p align="center">
	<img src="screenshots/tile440x280.png">
<p>

## Supported IDEs:

* VS Code
* VS Code Insiders
* PhpStorm
* WebStorm (not tested yet)

PhpStorm support is native on MacOS, but on Linux and Windows you need to install an url handler:

* Linux: https://github.com/sanduhrs/phpstorm-url-handler
* Windows: https://github.com/aik099/PhpStormProtocol

I have not tested WebStorm support yet, feedbacks are welcome!

## New features & bugs

Need a feature? Want to report a bug? Feel free to open an issue or a pull request!

## Changelog

### Version 1.1.2 - July 1, 2019

* Fix blurry icons on Retina screens

### Version 1.1.1 - June 20, 2019

* Use popup instead of options page

### Version 1.1.0 - June 16, 2019

* Show editor icon instead of line number when hovering over a line in file blocks
* Add options to select where to show the icon in GitHub
* Add option to show debug messages in console
* Fix some bugs

### Version 1.0.3 - June 15, 2019

* Add PhpStorm support

### Version 1.0.2 - June 14, 2019

* Add missing VS Code Insiders icon

### Version 1.0.1 - June 14, 2019

* Add VS Code Insiders support
* Add CSS theme for options page
* Open options page automatically after install

### Version 1.0.0 - June 6, 2019

* First release!
* Add VS Code support
