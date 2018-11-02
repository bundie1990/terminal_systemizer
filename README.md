## App Systemizer (Terminal Emulator)
[More info and details in the XDA Thread](https://forum.xda-developers.com/apps/magisk/module-terminal-app-systemizer-ui-t3585851)

 Systemize your App systemlessly!
 Using terminal emulator.
 Enter this command and choose the app you want to systemize.

	systemize

or

	systemize -h
	
 And you will be presented with a list of installed apps.
 And Reboot to apply changes.

## Error?
 Go to the menu and type `logs`, this will upload the log files of this module and will generate a link. Send that :)
 Alternatively, Send `/cache/terminal_debloater-verbose.log` in the XDA thread. I'll examine it for problems and will try to fix it.

## Changelog

### v15.1
* Update mod-util
  * This contains a fix for the ProgressBar on small devices (with small dpi)
* Misc improvements
### v15
* Properly fix systemizing when magisk.img is out of space
* Misc improvements
### v14.3
* Fix an error in systemizing large apps
* Move systemize to xbin
* Misc improvements
### v14.2.1
* Misc improvements
### v14.2
* Re-add root detection
* Include app libs when systemizing
### v14.1
* Update module template
### v14
* Add Set SELinux option to make app detection faster
* Make "Enter Label" option faster and more efficient
* Name apk to it's parent folder
* Misc improvements
