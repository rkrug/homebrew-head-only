THIS REPOSITORY IS OUTDATED AND NOT FUNCTIONAL ANYMORE
================
Please use the https://github.com/OSGeo/homebrew-osgeo4mac tap and the formulas in it to install grass from there.



````
brew install --HEAD osgeo-grass 
````

should install grass from the master branch on github.

Homebrew Recipie for GRASS trunk
================
Rainer M Krug <Rainer.Krug@uzh.ch>

[![Build Status](https://travis-ci.org/GRASS-GIS/homebrew-grass-dev.svg?branch=master)](https://travis-ci.org/GRASS-GIS/homebrew-grass-dev)

---

This [homebrew](https://brew.sh) Tap contains recipes to build [GRASS trunk](https://grass.osgeo.org/development/svn/). They should be working, but nothing is guaranteed!

To use it, you have to first tap the repository:
```
brew tap GRASS-GIS/homebrew-grass-dev
```

after that, you can use

````
brew install --HEAD grass-trunk
````

to install the current development version of GRASS.

All contributions are welcome.

If you have questions, problems, suggestions, etc, please use the issue tracker.
