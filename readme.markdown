Sublime Text 3 Redmine
=========================

Overview
--------
View your assigned redmine issues in the quick panel, and opens your selection in a web browser.
This plugin is [Sublime-Text-Redmine-Plugin] by [blakeanderson], reworked for ST3

Installation
------------

Go to your Sublime Text 3 `Packages` directory

 - OS X: `~/Library/Application Support/Sublime Text 3/Packages/`
 - Windows: `%APPDATA%/Sublime Text 3/Packages/`
 - Linux: `~/.Sublime Text 3/Packages/`
 - Ubuntu: `~/.config/sublime-text-3/Packages/`

and clone the repository using the command below:

``` shell
git clone https://github.com/abracadaber/Sublime-Text-Redmine-Plugin.git Redmine
```

Settings
--------
For the plugin to work, you will need to update Redmine.sublime-settings

Add your redmine url, user id, username, and password, then your set.

`Redmine.sublime-settings`

	{
		// Redmine URL
		"redmine_url": "", 

		// Redmine User ID: click logged in as 'username' and enter number on the very right of the url
		"redmine_user_id": "",

		// Redmine Username
		"username": "",

		// Redmine Password
		"password": ""
	}


Usage
-----

 - View issue: `Command-Shift-M`

Keys:
 'Command' (OSX)
 'Ctrl' (Linux / Windows)

 [ianepperson]: https://github.com/ianepperson
 [Sublime-Text-Redmine-Plugin]: https://github.com/blakeanderson/Sublime-Text-Redmine-Plugin
