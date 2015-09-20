Cube Bootstrap 3 Theme

CSS:
- Theme includes SASS version (SCSS) and also compiled css filed.
- SCSS folder includes only SASS version with CodeKit config included.
- LESS folder includes only LESS version with CodeKit config included. It’s port from SCSS version.
- CSS folder includes compiled SASS version for deployment.

CSS Styles (in css folder):
- The /compiled folder includes all major styles of the theme.
- The /bootstrap folder includes the bootstrap files. Bootsrap libs are not changed.
- The /lib folder includes the styles for the plugins.
- Added classes .hidden-xxs and .visible-xss for showing/hiding content on 420px's devices and smaller.

SCSS & LESS Folder:
- Bootstrap folder includes Bootstrap SASS (or LESS) version.
- Theme folder includes thw whole theme files, which should be self explanatory.

Scripts:
- Javascript code for every page is located at the end of each html template file, so you don't have to include all plugins for every page.

Icons:
- FontAwesome icons
- Glyphicons - if you move the location of bootstrap files, you need to change the relative path to icons in it.

Html:
- indexTEMPLATE.html includes empty template without content in the main content area.
- all other files includes content based on each type.
- errors - there are more versions of error files and each error file has more versions of images.
- logins - there are two version of logins.

Skins - Theme has 8 possible skins:
- Default
- White/Green - add class "theme-white" to body element of every page
- Blue Gradient - add class "theme-blue-gradient" to body element of every page
- Amethyst - add class "theme-amethyst" to body element of every page
- Blue - add class "theme-blue" to body element of every page
- Red - add class "theme-red" to body element of every page
- White/Blue - add class "theme-whbl" to body element of every page
- Green Sea - add class "theme-turquoise" to body element of every page

Layout Options:
- Fixed Header - add class "fixed-header" to body element of every page
- Fixed Footer - add class "fixed-footer" to body element of every page
- Fixed Left Menu - add class "fixed-leftmenu" to body element of every page
- Boxed Layout - add class "boxed-layout" to body element of every page
- RTL Layout (Right-to-Left) - add class "rtl" to body element of every page

Change Log:
v 1.12 - 2015/08/18
- Updated: Daterangepicker to Latest version 2.0.8

v 1.11 - 2015/08/11
- Updated: Fullcalendar to Latest version 2.3.2
- Updated: Moment.js to Latest version 2.10.6
- Fixed week view in fullcalendar example with update Moment.js

v 1.10 - 2015/04/29
- Updated: Less version of files for previous release
- Fixed nice radio and checkbox support for latest Safari

v 1.9 - 2015/04/20
- Updated: Fullcalendar to Latest version 2.3.1
- Updated: Select2 to Latest version 4.0.0-rc.2

v 1.8 - 2015/03/08
- New Feature - Foo Tables plugin added
- Fixed Less files - there were missing some css changes

v 1.7 - 2015/02/06
- Fixed usage of datepicker and daterangepicker in modal (changes are made only in css)

v 1.6 - 2015/02/04
- Updated: Timepicker to Latest version 0.2.5 - fixes usage of timepicker in modal

v 1.5 - 2015/01/27
- Fixed Tabs for AngularJS with new directive
- Fixed small bugs in AngularJS files

v 1.4 - 2015/01/18
- Fixed minor bugs on responsive in main css file
- Updated: DropzoneJS to Latest version 3.12.0
- Updated: Dygraphs to Latest version 1.1.0
- Updated: DataTables to Latest version 1.10.4
- Updated: Morris charts to Latest version 0.5.1
- Updated: Summernote to Latest version 0.6.0

v 1.3 - 2015/01/13
- Small CSS bugfix for date and time pickers - changes only in theme_styles.css

v 1.2 - 2015/01/05
- Small fix for Less port
- Fix for DropzoneJS implementation in AngularJS version

v 1.1 - 2014/12/23
- Fix for dropdown menu in Safari - changes only in CSS files