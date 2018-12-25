# Unofficial Snap Packaging for The XSLT C library for GNOME
<!--
​	Use the Staticaly service for easy access to in-repo pictures:
​	https://www.staticaly.com/
-->
![Icon of The XSLT C library for GNOME](gui/libxslt.adapted.png "Icon of The XSLT C library for GNOME")

**This is the unofficial snap for The XSLT C library for GNOME**, *"An XSLT C library developed for the GNOME project"*. It works on Ubuntu, Fedora, Debian, and other major Linux distributions.

[![Build Status Badge of the `libxslt` Snap](https://build.snapcraft.io/badge/Lin-Buo-Ren/libxslt-snap.svg "Build Status of the `libxslt` snap")](https://build.snapcraft.io/user/Lin-Buo-Ren/libxslt-snap)

![Screenshot of the Snapped Application](local/screenshots/version.png "Screenshot of the Snapped Application")

Published for <img src="http://anything.codes/slack-emoji-for-techies/emoji/tux.png" align="top" width="24" /> with 💝 by Snapcrafters

## Installation
([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

### In a Terminal
    # Install the snap #
    sudo snap install --channel=beta libxslt
    #sudo snap install libxslt
    
    # Connect the snap to optional security confinement interfaces #
    ## For accessing files under `/media`, `/run/media` or `/mnt` ##
    sudo snap connect libxslt:removable-media
    
    # Launch the application #
    libxslt.xsltproc

    ## If you want to use the `xsltproc` alias
    snap alias libxslt.xsltproc xsltproc
    xsltproc

### The Graphical Way
[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/libxslt)

## What is Working
* [The examples on the XSLT Wikipedia article](../test-cases/xslt-wikipedia-article/README.md)

## What is NOT Working...yet 
Check out the [issue tracker](https://github.com/Lin-Buo-Ren/libxslt-snap/issues) for known issues.

## Support
* Report issues regarding using this snap to the issue tracker:  
  <https://github.com/Lin-Buo-Ren/libxslt-snap/issues>
* You may also post on the Snapcraft Forum, under the `snap` topic category:  
  <https://forum.snapcraft.io/c/snap>

