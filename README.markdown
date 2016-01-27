JetBrains Web IDE Editor Colour Schemes
=======================================

Editor colour schemes based on the the [original Solarized colour scheme][Solarized repository] developed by:

- Ethan Schoonover <es@ethanschoonover.com> 

Adapted as [JetBrains WebIDE Solarized colour schemes][IntelliJ-only repository] by:

- Adam Vandenberg <flangy@gmail.com>  
- Johan Kaving <johan@kaving.se>

Installation
------------

1. Go to `File | Import Settings…` and specify this directory or the `settings.jar` file it contains.
1. Click `OK` in the dialog that appears.
1. Restart the JetBrains IDE when prompted.
1. Go to `Preferences | Editor | Colors & Fonts` and select one of the new colour schemes.

Visit the [Solarized homepage]
------------------------------

See the [Solarized homepage] for screenshots, details and colorscheme versions for Vim, Mutt, popular terminal emulators and other applications.

[Solarized homepage]:   http://ethanschoonover.com/solarized
[Solarized repository]: https://github.com/altercation/solarized
[IntelliJ-only repository]:  https://github.com/jkaving/intellij-colors-solarized


Important Notes
---------------

### Font Settings

Unfortunately, font settings are included with JetBrains WebIDE editor colours. You may wish to modify these in `Preferences | Editor | Colors & Fonts | Font` after adding the colour schemes to your JetBrains WebIDE installation.

### Committing Changes

If you want to commit updates to the XML color scheme files, make sure to run the `build.sh` script before committing to generate an updated `settings.jar` file. This build script has been tested on Mac OSX and Linux. 

If you are using Windows and would like to commit a build script for the Windows platform, please do. It is a very simple shell script that should work from a Cygwin terminal but could equally be written as a BATCH script (`build.bat`) or using JScript in the Windows Scripting Host (`build.wsh`) or some other similar Windows scripting language. 


