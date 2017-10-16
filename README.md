# Paper Extra Icons

Custom icons for Paper Icon Theme of the [Paper Project](https://snwh.org/paper) made by [Sam Hewitt](http://snwh.org/).

![](Paper/48x48/apps/vineyard.png)
![](Paper/48x48/apps/mega.png)
![](Paper/48x48/emblems/mega-synced.png)
![](Paper/48x48/emblems/mega-pending.png)
![](Paper/48x48/emblems/mega-syncing.png)
![](Paper/48x48/mimetypes/application-mathematica.png)
![](Paper/48x48/mimetypes/text-x-matlab.png)
![](Paper/48x48/mimetypes/text-x-python3.png)
![](Paper/48x48/mimetypes/text-x-r-markdown.png)
![](Paper/48x48/mimetypes/application-x-r-project.png)
![](Paper/48x48/mimetypes/application-epub+zip.png)
![](Paper/48x48/mimetypes/application-x-mobipocket-ebook.png)
![](Paper/48x48/mimetypes/application-vnd.adobe.adept+xml.png)
![](Paper/48x48/mimetypes/text-x-tex.png)
![](Paper/48x48/mimetypes/text-x-bibtex.png)
![](https://github.com/snwh/paper-icon-theme/blob/master/Paper/48x48/mimetypes/application-x-executable.png)
![](https://github.com/snwh/paper-icon-theme/blob/master/Paper/48x48/mimetypes/application-x-rar.png)

Paper is a free culture icon theme by Sam Hewitt and is licenced under the terms of the [Creative Commons Attribution-Share Alike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/), unless otherwise specified.

## Downloading the original Icon Theme

The original source for Paper Icon Theme can be found [here](https://github.com/snwh/paper-icon-theme). You can clone the latest version from the git repository:

	git clone https://github.com/snwh/paper-icon-theme.git

## Using the Source

There are scripts to simplify the rendering process; to run them (and edit icons) you will need:

 * inkscape
 * python3
 * gtk-engine-murrine (optional)

To render new icons from their source SVG files, run the following:

	python render-bitmaps.py

If it's throwing an error, the script may not be executable, try:

	chmod +x render-bitmaps.py

This script will look in the source directory `(../src/*)` and render the respective icons (provided there are changes).

## Installation

Simple, you just run the script from the root of the source folder:
```bash
./INSTALL
```
Keep in mind that you need to have the original Paper Icon Theme for some symbolic links to work.
