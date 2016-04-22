garmin-dev
==========

A set of utilities for converting *.gmn files to *.tcx files for upload to the
Garmin Connect website.

I have not developed the whole code in this repository, just the glue.  However, the licenses allow
for the free distribution of the contents as far as I can tell.  If this is not
the case, please let me know and I will take appropriate actions.

Ubuntu 14.04
------------
Install used packages
```
sudo apt-get install libxml2-utils libsaxonb-java garmin-forerunner-tools
```
Move files
```
sudo mv gmn2tcx /usr/local/bin/
sudo mv gmn2tcx.xslt /usr/local/bin/
sudo mv tcx.xsd /usr/local/bin/
sudo mv read_garmin_305 /usr/local/bin/
sudo mv 70-usb-custom.rules /etc/udev/rules.d/
```
Edit /usr/local/bin/read_garmin_305 
