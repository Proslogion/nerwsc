# nerwsc

## Description

This is an Oxygen Author framework made by using the [Oxygen Addon Builder](http://kuberam.ro/oxygen-addon-builder/ "Oxygen Addon Builder"), for the use of the project [Wissenschaftssprache Chinesisch (WSC) of the Cluster of Excellence Asia and Europe](http://kjc-sv016.kjc.uni-heidelberg.de:8080/exist/apps/wsc/modules/search/aboutus.html "Wissenschaftssprache Chinesisch").

The update site url is [https://github.com/claudius108/nerwsc/raw/master/target/addon.xml](https://github.com/claudius108/nerwsc/raw/master/target/addon.xml "nerwsc framework").

## Scope

The scope of this framework is to allow users to proofread *placeName*, *persName*, *orgName*, and *date* TEI elements as descendants of *note* TEI elements. The proofreading is done using Oxygen Author View.

Actions on the *placeName*, *persName*, *orgName*, and *date* elements the user is able to take:
* changing any element to any of the other elements;
* deleting any element;
* wrapping of an arbitrary text content in any of these elements.
 
## User interface

Only the *note* elements and their contents are displayed.

Each of the *placeName*, *persName*, *orgName*, and *date* TEI elements has buttons for replacing with any of the others and a delete button.

The buttons for wrapping the selection of text are located at the beginning of the respective *note* element.

The tags for elements are not displayed, in order to have a simple user interface.

The users cannot switch to Page view.

![nerwsc screenshot](/resources/images/screenshot.png)


## Icons

The icons used were created by Matt Gentile from http://www.icondeposit.com/.
  

## Changelog:

**Version 1.0.8 - 2015.03.20**

1. The framework was renamed to nerwsc, and the codebase was moved to github at https://github.com/claudius108/nerwsc.
2. The update site url is now https://raw.githubusercontent.com/claudius108/nerwsc/master/target/addon.xml.

**Version 1.0.7 - 2015.03.20**

1. This version allows users to wrap the selection by using the buttons located after the 'Note' text (light green as background colour).

**Version 1.0.6 - 2015.03.20**

1. This version allows wrapping selection in the needed elements, by accessing the menu items of the contextual menu (right click after making the selection).

**Version 1.0.5 - 2015.03.19**

1. This version contains the toolbar with buttons for wrapping the selection in elements. The button are not active yet. Starting with Oxygen v. 17 it will be possible
to have only one floating toolbar, but for now the only solution is to have one toolbar for each 'note' element.

**Version 1.0.4 - 2015.03.18**

1. This version the new very nice icons.

**Version 1.0.4 - 2015.03.17**

1. The current version should be able to be installed in Oxygen.

**Version 1.0.3 - 2015.03.17**

1. First Oxygen installable version.

**Version 1.0.2 - 2015.03.17**

1. This version has main action.

**Version 1.0.1 - 2015.03.16**

1. Very first version.
