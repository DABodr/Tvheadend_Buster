# Install Tvheadend on Debian Buster

*Add the following line to /etc/apt/sources.list:

deb http://www.deb-multimedia.org buster main

*copy/past:

sudo apt-key adv --keyserver hkps://keys.gnupg.net --recv-keys 5C808C2B65558117

sudo apt-get update

sudo apt-get install deb-multimedia-keyring

*Install tvheadend deb package:
 sudo apt-get install tvheadend
