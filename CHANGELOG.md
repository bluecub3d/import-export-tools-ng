# ImportExportTools NG Changelog

## Versions

Version 4.1.0 : New Features - April 1, 2020

- Help/User guide : Fully localized
- Suffix option for filenames
- Custom date option for filenames allowing strftime() like full date and time formatting
- Use custom file naming for both attachments and embedded attachments
- Custom date option for index filenames
- Option to use 'Received Date' for filename and index
- User configurable Hotkeys (Keyboard shortcuts)
- PDF output now uses the global print options
- Improved HTML index file layout

Bug Issues Fixed:
- #68 fix for index attachment flag
- #74 fix for in-line image attachments not exported
- Fix #56 handle cancel on import dialog
- #77 use preferences for PDF output
- UI cleanup tweaks (#80, #81, #82 ) OS variations - @ovari
- German translation fix #93 - @dipgithub
- Hungarian translation fixes - @ovari
- Add missing license file #96 

Thanks to the following users for enhancement suggestions and test help, contributions:
@ovari
@dipgithub
@artofit
@JF1313
@jessejmorrow
@spd2000 
@kanlukasz 
@razzmatazzz 
@triplee

4.0.4 Maintenance  Release - September 16, 2019 
- Fixed text formatter signature change
- Fixed handling of import filenames > 55 characters

4.0.3 Maintenance  Release - September 12, 2019 
- Fixed EML import issue
- Fixed HTML layout for text attachments

4.0.2 Maintenance  Release - September 10, 2019 
- Fixed plaintext/HTML attachment export
  String.trim test failing - String generics deprecated
  Fixes #13
- Remove remaining Components.*
- Fix HTML export format for embedded images
  Change file pointer fixup 
  Move image into fieldset

4.0.1 Maintenance  Release - August 15, 2019 
 - Fixed warning for deprecated menu overlay task popup
   Fixes #9 
 - Use createXULElement for TB68+
   Fixes #8 , TB69 Beta compatibility

4.0.0  Initial NG Release - July 19, 2019 
 - Updated for TB68
 - New name and icon
 - Updated formatting
 - Options dialog tweaks, icon

## Original Extension:

3.3.2  Update for TB60 - January 27, 2019
 - Last version update by "Kaosmos"
