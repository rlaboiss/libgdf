libGDF
======

C++ implementation of GDF - "a general dataformat for biosignals" version V2.20. 

Obtaining libGDF
----------------

Use the following command to fetch the sources:

    git clone https://github.com/kazemakase/libgdf.git libgdf
    
Dependencies
------------
Required: boost

Build Instructions
------------------

The preferred method is to perform an out-of-source build.
replace `$GDF_ROOT with the` (relative or absolute) path to the source
tree (e.g. ~/SVN/GDF/trunk).

    mkdir build
    cd build
    cmake $GDF_ROOT
    make
    make check