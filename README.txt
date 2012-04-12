LessCSSConverter
================

version: 1.0
release: 5 march 2012
author: Francesco Illuminati (fillumina@gmail.com)
license: apache 2.0
see: http://lesscss.org

This is a simple Java desktop application that use the LessCSSLib to convert
a LessCSS file into a standard CSS file. The maven file uses the izinstall
library to build a simple installer. The application uses an internal version
of less.js (actually version 1.3.0) but an external one may be provided.

The project uses maven 2.0 so you can build and install the library by issuing

mvn clean install

in the main directory.