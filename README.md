Photoshop-Export-Layers-as-Images
=================================

<b>This script allows you to export layers in your Photoshop document as individual images</b> at a speed much faster than the built-in script from Adobe. So far it does not feature all the formats that the built-in version does, but more can be added easily upon request. Feel free to contribute to it and make it even more powerful!

This script was originally built as a response to a [question](http://graphicdesign.stackexchange.com/questions/1961/export-photoshop-layers-to-individual-png-files-batch-process) on [graphicdesign.stackexchange.com](http://graphicdesign.stackexchange.com/).

Make sure to download all files:

<b>[Download as zip](https://github.com/jwa107/Photoshop-Export-Layers-as-Images/archive/master.zip)</b>

Features:
-------------------------------
* Supported export formats:
  * PNG (8 and 24 bit)
  * Targa 
  * JPEG
* Handles nesting in grouped layers.
* Export either all layers or visible only.

You can also see [what's coming next](https://github.com/jwa107/Photoshop-Export-Layers-as-Images/wiki/Feature-Roadmap) and browse some of our [performance test results](https://github.com/jwa107/Photoshop-Export-Layers-as-Images/wiki/Performance-Test-Results).

Requirements: 
-------------------------------
Adobe Photoshop CS2 or higher.

How To Use: 
-------------------------------
1. Open Photoshop
2. File -> Scripts -> Browse...
3. Locate the file, and open it.

Alternatively move the script into the /presets/scripts directory, located by in your Photoshop folder.

Windows: /Program Files/Adobe/Adobe Photoshop VERSION/Presets/Scripts/

Mac: /Applications/Adobe Photoshop VERSION/Presets/Scripts/


Version History:
-------------------------------

<b>8 June 2014</b> by [Skjorn](https://github.com/skjorn)

* Script renamed to match the built-in version.
* The dialog extended.
* Destination folder made selectable.
* Added an option to export only visible layers and fixed visibility toggling after export.
* The script made faster!
* The document doesn't have to be saved and be a layered PSD anymore. Exporting from a temporary working copy is fine.
* Major rewrite of internals.

<b>22 May 2014</b> by [Skjorn](https://github.com/skjorn)

* Added support for Targa (TGA).

<b>2 December 2013</b> by [Justin Wang](http://www.github.com/Tangleworm)

* Added support for both PNG-24 and PNG-8

<b>24 May 2013</b> by [Johannes Walter](https://github.com/jwa107)

* Nesting properly handled
*  All layers save seperately again (no more stacking).

<b>27 March 2013</b> by [Robin Parmar](http://robinparmar.com/) (robin(at)robinparmar(dot)com)

* preferences stored in object
* auto-increment file names to prevent collisions
* properly handles layer groups
* header added
* code comments added
* main() now has error catcher
* counts number of layers
* many little code improvements

<b>26 Sept 2012</b> by [Johannes Walter](https://github.com/jwa107)

* Original version


Contact:
-------------------------------
Please use communication channels on GitHub to write feedback/bugs/suggestions: https://github.com/jwa107/Photoshop-Export-Layers-as-Images/issues
