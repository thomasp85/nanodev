<!-- README.md is generated from README.Rmd. Please edit that file -->
nanodev
=======

[![Travis-CI Build Status](https://travis-ci.org/thomasp85/nanodev.svg?branch=master)](https://travis-ci.org/thomasp85/nanodev) [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/thomasp85/nanodev?branch=master&svg=true)](https://ci.appveyor.com/project/thomasp85/nanodev) [![CRAN\_Release\_Badge](http://www.r-pkg.org/badges/version-ago/nanodev)](https://CRAN.R-project.org/package=nanodev) [![CRAN\_Download\_Badge](http://cranlogs.r-pkg.org/badges/nanodev)](https://CRAN.R-project.org/package=nanodev)

**HIGHLY EXPERIMENTAL WIP - DOES NOT WORK**

In order for R to produce graphics it must have a device to put the graphics in. Many of these exists, both window-based (e.g. `X11()`) and file-based (e.g. `png()`). While the graphics performance of R is highly dependent on the performance of your plotting R code, as well as the underlying base or grid graphics code it calls, the speed of the graphics device is also important as it defines the speed with which the graphic instructions can be executed. `nanodev` is an attempt to provide a modern, fast, high quality graphic device for R based on the [NanoVG](https://github.com/memononen/nanovg) C++ library, which provides an antialiased 2D vector drawing library on top of OpenGL.
