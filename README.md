QDjango - a Qt-based C++ web framework  
Copyright (c) 2010-2012 Jeremy Lainé

[![Build Status](https://travis-ci.org/jlaine/qdjango.png)](https://travis-ci.org/jlaine/qdjango)

About
=====

QDjango is a web framework written in C++ and built on top of the Qt library.
Where possible it tries to follow django's API, hence its name.

It is released under the terms of the GNU Lesser General Public License, version 2.1 or later.

Requirements
============

On Debian
----------

    sudo aptitude install libqt4-dev libqt4-sql-sqlite

On Mac OS X
-----------

    sudo port install qt4-mac

Building QDjango
================

    mkdir build
    cd build
    qmake ..
    make

You can pass the following arguments to qmake:

    PREFIX=<prefix>                 to change the install prefix
                                    default:
                                        unix:  /usr/local on unix
                                        other: $$[QT_INSTALL_PREFIX]
    QDJANGO_LIBRARY_TYPE=staticlib  to build a static version of QDjango

Mailing list
============

If you wish to discuss QDjango, you are welcome to join the [QDjango group](http://groups.google.com/group/qdjango).