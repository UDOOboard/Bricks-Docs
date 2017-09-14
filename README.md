# UDOO Bricks Documentation

Travis build status: [![Build Status](https://travis-ci.org/UDOOboard/Bricks-Docs.svg?branch=master)](https://travis-ci.org/UDOOboard/Bricks-Docs)

This repository contains the source code for the documentation hosted at [www.udoo.org/docs-bricks/](http://www.udoo.org/docs-bricks/).


## Build the documentation locally
On PHP7+ install XML and mbstring modules:

    sudo apt-get install php7.0-xml php7.0-mbstring

Then build the documentation with

    ./daux.phar && ( cd static; cp -rp ../img .)

To serve the documentation from a development webserver, run

    cd static && php -S localhost:8080


