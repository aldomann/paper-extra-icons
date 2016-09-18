Paper Extra Icons
===================

Custom icons for Paper Icon Theme of the [Paper Project](https://snwh.org/paper) made by [Sam Hewitt](http://snwh.org/).

Paper is a free culture icon theme by Sam Hewitt and is licenced under the terms of the [Creative Commons
Attribution-Share Alike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/), unless otherwise specified.

###Downloading the original Icon Theme

The original source for Paper Icon Theme can be found [here](https://github.com/snwh/paper-icon-theme). You can clone the latest version from the git repository:

	git clone https://github.com/moka-project/paper-icon-theme.git

###Using the Source

There are scripts to simplify the rendering process; to run them (and edit icons) you will need:

 * inkscape
 * python3

To render new icons from their source SVG files, run the following:

	./render-bitmaps.py
	./render-bitmaps-hidpi.py

If it's throwing an error, the script may not be executable, try:

	chmod +x render-bitmaps.py
	chmod +x render-bitmaps-hidpi.py

This script will look in the source directory (../src/*) and render the respective icons (provided there are changes).

-----------
