## Fork of quarnster/SublimeClang to provide Eero support. Highly experimental at this point.

See the original [README](https://github.com/eerolanguage/SublimeClang/blob/master/README.creole) for additional information.

### Installation

The Eero version is not currently installable via Package Control. Instead, clone this repo directly into your
packages directory. Make sure to use the `--recursive` switch:

    git clone --recursive https://github.com/eerolanguage/SublimeClang.git

A couple of native libraries are required. One of them, `libcache.dylib`, is provided in this repo for OS X x86_64.
The other, `libclang.dylib`, is assumed to be installed at `/usr/local/eerolanguage/lib/`. If you have it installed elsewhere,
just change the link in the `SublimeText/internals` directory to point to the lib in the other location.








