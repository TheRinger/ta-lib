
# ta-lib with latest libtool and subdir fix
Updated compilation files for installation on linux with latest libtool original src ->  https://ta-lib.org/hdr_dw.html


to install cd into dir then run 'brew config' to get prefix path
CFLAGS adds the MATH Library for doing complex math, sqrt, etc -  libm
```sh
 ./autogen.sh
 export CFLAGS=-lm && ./configure --prefix=/home/linuxbrew/.linuxbrew/Cellar/ta/lib
 make
 make install
```
installing without brew use 'sudo make install' and your prefix should be /usr/lib/ta or something like that.
[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)
