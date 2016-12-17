zlib for XCode
==========

This repository depends on https://github.com/leico/zlib depends on https://github.com/madler/zlib

usage
-----

1. clone and move repository
    '''
    https://github.com/leico/zlib-xcode
    cd zlib-xcode
    '''
1. move and clone zlib submodule
    '''
    git submodule update --init --recursive
    '''
1. zlib configure, automodify zconf.h
    '''
    cd zlib
    ./configure
    '''
