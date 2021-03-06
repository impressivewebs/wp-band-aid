# WP Band Aid

An extension to help with common tasks around the WP back end.

Not really useful for external use (yet).

Install via [this link](https://chrome.google.com/webstore/detail/wp-band-aid/aeceeddcjnflciomahopkpgklnfjebib).

## Features

- automatically checks for presence of [author_more] tag in the text, and makes the field glow red if this tag is absent
- checks for relative links in text, warns about them
- provides Capitalize option under the title, which instantly titlecapitalizes it
- provides Copy Tags button under Tags, so you get a comma separated list of tags copied to the clipboard, in case you need to reuse them on another post
- the series input field which typically allows you to add a new series right from the Add / Edit post page now also serves as an insta-filter. Just type into it and unwanted series automatically hide
- removed Total Cache header popup
- headline analyzer included in the UI
- the schedule fields for date and time have been replaced with a datepicker
- the subheadings in the text can now also be programatically capitalized - new button added under the title field
- removed the "Publish to Discourse" checkbox
- removed the "Is this headline OK" button (not needed since we've got the analyzer built in now)
- makes the syntax highlighter default to the selected primary category, if there's a match
- buttons "Copy Link" and "Rebuild Link" were added next to the permalink part, under the title field. The Rebuild one refreshes the slug if you changed the title, and the Copy one copies the full link (http://sitepoint.com prefix and all) to the clipboard.
- added context menu option which lets users copy the title / description of the current page, or if right clicking on a link, the title / description of the target page. Useful when writing newsletter.