## Changelog
### v0.56.67
Bug-Fixes:
* Fixed repetitive on-demand prompts
* Fixed on-demand prompts for system and kernel
* Internal restructuring of process parsing
* Fixed bugs reported through the in-built error reporter

Features:
* Added and updates languages

- --

### v0.56.66
Bug-Fixes:
* Fixed UI-Glitches
* Fixed all reported bugs

Features:
* Added the possibility to one-click remove all privacy settings
* Restructured parts of the preferences categories
* Updated translations
* Added language: Chinese, thx @surwscl, @aqinny

- --

### v0.56.65
Bug-Fixes:
* Fixed errors reported through the built-in error report
* Several bug fixes

Features:
* ...

- --

### v0.56.64
Bug-Fixes:
* Fixed internet restriction
* Several layout improvements

Features:
* ...

- --

### v0.5.59-63
Bug-Fixes:
* Fixed Gui-Glitches
* Layout improvements
* Fixed initial restriction count, triggered by the on demand dialog
* Fixed contact picking bug
* Performance improvements
* Reduced battery usage
* Fixed FC on ICS-Devices (API 15)
* Several Bug-fixes reported through the built-in error report

Features:
* Implemented pro feature in-app shop where you can buy additional pro features
* Revamped filter logic

- --

### v0.5.58
Bug-Fixes:
* Fixed Gui-Glitches within the settings activity

Features:
* Revamped Read/Write external storage permission
* Added language: Spanish, thx @[dukelc](http://www.getlocalization.com/user/dukelc)
* Added language: Turkish, thx @[lastdark](http://www.getlocalization.com/user/lastdark)
* Added language: Slovak, thx @[Ocab19](http://www.getlocalization.com/user/Ocab19)

- --

### v0.5.57
Bug-Fixes:
* Temporary disabled read/write external storage permission, because of heavy battery drainage on some devices

Features:
* DonkeyGuard Location Picker is now available at [PlayStore](https://play.google.com/store/apps/details?id=eu.donkeyguard.locationpicker)

- --

### v0.5.56
Bug-Fixes:
* Fixed possible FC with API 15 (ICS)
* Fixed UI-Instructor glitches

Features:
* Minor internal refactoring to support Add-Ons
* Added compatibility with Location Picker Addon

- --

### v0.5.55
Bug-Fixes:
* Fixed unsupported API 15
* Minor layout improvements
* Added the ability to hide a hint dialog
* Improved dialog layouts
* Improved hints

Features:
* Enabled LOG feature for non-pro user (with limited information)

- --

### v0.5.54
Bug-Fixes:
* Fixed internet-restriction bug (FC due to multithreading bug)

Features:
* Updated all languages
* Pre-Prepared for location-picker plugin

- --

### v0.5.53
Bug-Fixes:
* Fixed possible Layout-Bug for LG G3
* Fixed unnecessary database synchronization

Features:
* Implemented built-in error report

- --

### v0.5.52
Bug-Fixes:
* Minor layout improvements

Features:
* Implemented a "batch-switch" which enables the interception mode (on demand dialog) for all permissions of the application.
* Updated translations

- --

### v0.5.51
Bug-Fixes:
* Enhanced internet restriction
* Reduced memory usage
* Added dialog for cydia support information
* Enhanced database access (query) speed
* Fixed missing translations
* Enhanced some error dialogs
* Fixed device crashing because of network state request
* Fixed process parsing
* Massive internal refactoring & restructuring

Features:
* Prepared for log-feature (not accessible until now, because it will move to pro-version)
* Added feature to enable the interception mode for every new installed application
* Updated language: Romanian, thanks @[flashxml](http://www.getlocalization.com/user/flashxml)
* Updated language: Portuguese (Brazil) -> thanks @[xdxita](http://www.getlocalization.com/user/xdxita)
* Updated language: Japanese -> thanks @[WedyDQ10](http://www.getlocalization.com/user/WedyDQ10) & @[1341sakuya](http://www.getlocalization.com/user/1341sakuya)
* Updated language: French -> @[therealcorwin](http://www.getlocalization.com/user/therealcorwin)

- --

### v0.5.50
Bug-Fixes:
* Fixed filter manager rules

Features:
* Enhanced Internet restriction
* Enabled on demand for internet restriction
* Added language: Romanian, thanks @[flashxml](http://www.getlocalization.com/user/flashxml)

- --

### v0.5.49
Bug-Fixes:
* Enhanced battery usage 

Features:
* Added INTERNET restriction. It only works if you install the [Cydia-Framework](http://www.cydiasubstrate.com/). Known Issue: An existing connection (with an connection-based protocol) won't be disconnected by the rule, just reestablishing will be blocked ever after. So if you restrict Internet for an application, force close it or restart your device to be sure that it can't access the internet anymore.
* Added the possibility to save the decision from interception dialog to database. [More details](https://github.com/CollegeDev/DonkeyGuard/issues/7). Simply check the option "Don't ask again" and your decision will be saved.
* Updated language: Japanese -> thanks @[WedyDQ10](http://www.getlocalization.com/user/WedyDQ10)
* Updated language: Portuguese (Brazil) -> thanks @[xdxita](http://www.getlocalization.com/user/xdxita)


- --

### v0.5.48
Bug-Fixes:
* Revamped GPS restriction
* Enhanced battery usage (fixed bug where device isn't able deep sleep)
* Added support for HTC devices (HTC has a lot of own stuff inside the framework)
* Prepared for internet restriction

Features:
* Added language: Japanese -> thanks @WedyDQ10
* Added language: Hebrew -> thanks @BeBest
* Added language: Portuguese (Brazil) -> thanks @xdxita

- --

### v0.5.47
Bug-Fixes:
* Fixed GUI glitches within the settings screen

Features:
* Implemented a filter-manager

- --

### v0.5.45-46
Bug-Fixes:
* Fixed GPS Bug
* Several cleanups

Features:
* ...

- --

### v0.5.44
Bug-Fixes:
* Some refactoring for new features

Features:
* Prepared for auto-log fetching feature -> added Permission android.permission.READ_LOGS (needed to enable better log support)
* Implemented (beta) the UI-Instructor. Activate it with preference UI-Instructor to learn more about the UI.
* Added Icon to indicate internet access. (Please activate the UI-Instructor to see how it works).

- --

### v0.5.43
Bug-Fixes:
* Fixed XposedFramework validation

Features:
* ...

- --

### v0.5.42
Bug-Fixes:
* ...

Features:
* Enhanced checking for activation in XposedFramework.
* Prepared for UI-Instructor

- --

### v0.5.41
Bug-Fixes:
* Fixed wrong resources usage for some dialogs
* Refactoring for new features

Features:
* ...

- --

### v0.5.40
Bug-Fixes:
* Fixed FC of application while trying to enter in application search-mode (wrong resoure linking)
* Fixed style of overflow-button in settings menu
* Pre-preparing for native support
* Enhanced the copying procedure for the flashable Rescue-Zip (RescueDonkey.zip)
* Fixed FC at first start of the application, because of some resource conflicts

Features:
* ...

- --

### v0.5.39
Bug-Fixes:
* Reduced memory-cache to a maximum size of 5 MB for devices with small memory (512mb)
* Fixed EditText input flags which causes that the lat/lon input won't accept "." and "-"
* Enlarged Heap-Size on devices with enough memory
* Reduced memory usage of the application

Features:
* ...

- --

### v0.5.38
Bug-Fixes:
* ...

Features:
* Added changelog within the application (take a look at preference, category about).
* Added applicaton version within the application (take a look at preference, category about).
* Added the possibility to set all settings to: REAL, EMPTY, RANDOM within the settings activity.

- --

### v0.5.37
_Bug-Fixes:_
* Flush interception cache if the interception-mode changed
* Prevent that system_server can show interception dialogs to avoid freezing on some ROMs (this will change in future due to native support)
* Fixed NullPointerException during the force-close of the on-demand dialog

_Features:_
* Implemented toast messages for unimplemented features

- --

### v0.5.36
_Bug-Fixes:_
* Fixed parsing the default-deny-mode and default-privacy-mode at startup
* Internal code improvements (a lot of refactoring)

_Features:_
* Enabled application search (permission and rating is not enabled yet).

- --

### v0.5.35
_Bug-Fixes:_
- Fixed java.lang.NoSuchMethodError at ActivityManagerService for CM-11

_Features:_
- ...

- --


