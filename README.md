Paper Icon Theme
===================

Paper is simple and modern icon theme inspired by Google's material design.

Paper is a free culture icon theme by Sam Hewitt and is licenced under the terms of the [Creative Commons
Attribution-Share Alike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/), unless otherwise specified.

###Getting Paper

The Paper icons can be downloaded from [here](https://github.com/snwh/paper-icon-theme/archive/master.zip).

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
