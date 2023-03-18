# Photo-Tools

## Photo-SyncShrink

* mirrors source dir to target dir
* while shrinking jpegs in the target to 1920px at 75 quality
* configure via .ini file
* requires [ImageMagick](https://imagemagick.org)
* run via python or .exe file

## Photo-gen-taglist+gpx-tracks

* walks through a directory and its sub dirs
* reads date, gps location and tags of all jpeg files
* generates a 000000_gps.gpx track of all photos containing coordinates
* generates a 000000_tags.txt list of all tags/keywords assigned to photos
* generates a global 000000_tags_db.txt list containing per tags a list of dirs where it was used
