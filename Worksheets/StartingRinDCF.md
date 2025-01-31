Starting Up with R
================================
author: Daniel Kaplan
date:  June 12, 2013

Overview
================================

This file is an RStudio **presentation**.  
* It contains both narrative text and computer commands.

* It provides a way for us to distribute a coherent structure of  commands to you, so that you can revise incrementally.

By making small revisions, you learn the "programming" elements needed to guide your data analysis.

Packages
===============================

The DCF course makes use of the `DCF` package, custom written for the course.
* Easy-to-access data sets
* A coherent set of commands
* Graphical user interface for constructing graphics

Installing the DCF Package
==============================

We will install `DCF` by hand:

```r
require(devtools)
install_url("http://mosaic-web.org/go/Repository/DannyKaplan/DCF_0.13.tar.gz")
```


Installation is a one-time process.  So we may not need to do the above, or we may need to modify it depending on how your system is set up.

Loading DCF
==============================

At the start of each worksheet, you'll see the following command
`require(DCF)`.  This loads the package for your use.




