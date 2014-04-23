#Gforms SASS

Attempting to create a sass version of the default gravity forms (gforms) front end styles that can be modified/used to assist with creating custom gform styles.

The other goal is make it easier to combine and compress the multiple default gforms styles into one.

This is very early on - USE AT YOUR OWN RISK.

##Includes

Currently includes

* default stylesheets and images from gforms 1.8.7 in the /css and /images directories.
* first pass at scss conversion in the /scss directory
* I've started grouping and spitting some the formsmain styles into smaller scss files.

##Example Usage

`sass --watch --style compressed forms.scss:forms.css`

Will generate a compressed version of all front end styles into a single forms.css stylesheet

##To-dos

* Implement sass variables (image folder location, font size etc.)
* Give the default styles a good tidy and refactor without diverging from the default look and functionality
* Restructure the scss files as necessary

