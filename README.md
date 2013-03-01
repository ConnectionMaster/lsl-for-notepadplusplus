# Linden Scripting Language syntax highlight for Notepad++ #

last update: 2013-01-12

----------

![Screenshot](http://github.com/buildersbrewery/lsl-syntaxhighlight-for-notepadplusplus/blob/master/static/lsl_syntax_for_notepad_plus_plus.png)

----------

## Style definition for grammar and coloring: ##

* Create a new temporary XML file anywhere on your harddrive, then copy and paste the code from `userDefineLang.xml` in this repository into your file. Make sure the file's encoding is ANSI/ASCII!
* Open Notepad++ and go to `Language > Define your language > Import`
* Load previously saved file.
* When the import was successful close the language definition window and select `Language > LSL` from the menu. You should should be able to find the language at the bottom of the language menu in the section for user defined languages.
* You can now delete the temporary file.

## Language definition for autocompletion and tooltips (hints): ##

* Create a new XML file in the Notepad++ subdirectory `...\Notepad++\plugins\APIs\lsl.xml`
* Then copy and paste the code below into the file. Make sure the file's encoding is ANSI/ASCII!
* Goto `Settings > Preferences > Backup&Autocompletion` and make sure the autocompletion is enabled for words (not only functions) and the function hints are enabled.
