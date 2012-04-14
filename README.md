LessCSSConverter
================

- __version:__ 1.0
- __release:__ 5 march 2012
- __author:__ Francesco Illuminati (fillumina@gmail.com)
- __license:__ [apache 2.0](http://www.apache.org/licenses/LICENSE-2.0)
- __see:__ [lessCSS.org](http://lesscss.org "LessCSS.org")
[LessCSSLib](http://github.com/fillumina/LessCssLib)

This is a simple Java desktop application that uses the LessCSSLib to convert
a LessCSS file into a standard CSS file. The maven file uses the izpack
library to build a simple installer. The application uses an internal version
of less.js (actually version 1.3.0) but an external one may be provided.

The project uses maven so you can build and install the library by issuing

    mvn clean install

in the main directory.