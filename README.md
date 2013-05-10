Joomla! jFontSize Module
================
A Joomla! 2.5/3.X module implementation of the jQuery jFontSize JavaScript plugin from [http://www.jfontsize.com/](http://www.jfontsize.com/)

Options
-------

### Size Change Target
The html element, CSS class or ID to target. For exmaple, you can enter `body` to target the body element, or `.foo .bar` to target elements with the bar class, that are a decendant of elements with the foo class. 

### Plus Max Hits
Defines how many times the size can be increased.

### Minus Max Hits
Defines how many times the size can be increased.

### Size Change Interval
Defines the range of change in pixels.

Dependencies
------------
jQuery v1.2.6 or later
Joomla! 2.5 or later

Overriding the default stylesheet
----------
The default jFontSize module stylesheet can be overriden in the same way that you can override the layout with a template override. Simply place your CSS overrides in a stylesheet named jfontsize.css in the css directory of your template and it will be loaded instead of the default jFontSize stylesheet.

Stable Master Branch Policy
====================
The master branch will, at all times, remain stable. Development for new features will occur in branches, and when ready, will be merged into the master branch. Regular development and maintenance occurs in the [develop](https://github.com/betweenbrain/jFontSize-Module/tree/develop) branch.

In the event features have already been merged for the next release series, and an issue arises that warrants a fix on the current release series, the developer will create a branch based off the tag created from the previous release, make the necessary changes, package a new release, and tag the new release. If necessary, the commits made in the temporary branch will be merged into master

