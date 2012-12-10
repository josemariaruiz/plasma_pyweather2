plasma_pyweather2
=================

Fork of the plasmoid «plasma_pyweather» (http://opendesktop.org/content/show.php?content=110137)

The plasma_pyweather is licensed under GPL v3.
The information about GPL is available in gpl.txt file
Information about copying the script is in COPYING file.

It is a plasmoid written in python.

# Dependency: 
plasma-scriptengine-python, python-kde4, python-qt4

# How to Install

Use following command to install the .plasmoid file which is in fact a zip archive

$ plasmapkg -i plasma_pyweather.palsmoid

Unforutately, the gui for adding a new widget can only add binary widgets at the time of writing this.

# Create the package
If you download the whole source code e.g. from github, go to the extracted directory
and run the followig script

$ bash makePlasmoidPkg.sh

This will create the package plasma_pyweather.plasmoid in the parent directory.
