local (file system) "store" for usco project

General information
-------------------
This repository contains both the:
- node.js version:
fs-store.coffee in the src folder
- polymer.js/browser version which is a combo of
lib/fs-store.js (browserified version of the above)
fs-store.html


How to generate browser/polymer.js version (with require support):
------------------------------------------------------------------
Type: 

  grunt build-browser-lib

This will generate the correct browser(ified) version of the source in the lib folder

TODO: 
 - handle dependencies correctly : asset-manager should be kernel, and with a correct version number
