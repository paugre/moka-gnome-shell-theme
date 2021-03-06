Moka GNOME Shell Theme
======================

Moka is the titular GNOME Shell theme of the Moka Project.

Moka is distributed under the terms the GNU GPL v.3

###Preamble

If you find any bugs or issues with Moka or if you have a question, you can visit Moka's primary issue tracker on [GitHub](https://github.com/snwh/moka-gnome-shell-theme/issues).

###Download

Moka can be downloaded [here](http://www.mokaproject.com/moka-gnome-shell-theme/#download) for whatever you like.

###Getting the Source

The source for Moka GNOME Shell Theme can be found [here](https://github.com/snwh/moka-gnome-shell-theme).

Alternatively, you can clone the latest version its git repository:

    git clone https://github.com/snwh/moka-gnome-shell-theme.git

###Using the Source

There are scripts to simplify the rendering process; to run them (and edit icons) you will need:

 * inkscape
 * python3

To render new icons from their source SVG files, run the following:

    ./render-pngs.py

If it's throwing an error, the script may not be executable, try:
	
	chmod +x render-pngs.py

This script will look in the source directories (../src/*) and render the respective icons (provided there are changes).

-----------