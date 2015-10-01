***Works on OS X 10.11 El Capitan***

This is the Mac OSX binary for the stable release gcc-5.2.0, this file is provided for your convenience, if you prefer to compile yourself gcc-5.2.0 visit the tutorial webpage for build instructions:

[https://solarianprogrammer.com/2015/05/01/compiling-gcc-5-mac-os-x/](https://solarianprogrammer.com/2015/05/01/compiling-gcc-5-mac-os-x/)

**Clone (download) the archive on your machine with:**

git clone https://github.com/sol-prog/gcc-5.1.0-osx-binary

In order to install this binary extract gcc-5.2.0.zip and copy the extracted folder (gcc-5.2.0) in your /usr/local folder.

Using the new compilers (gcc-5.2.0, g++-5.2.0 and gfortran-5.2.0) require that you modify your shell path, paste the next line in a Terminal session:

export PATH=/usr/local/gcc-5.2.0/bin:$PATH

The above will modify temporarily your path (closing the Terminal will revert to the default path). If you want to add this permanently to your path add the above line in the .bash_profile file from your Home.

Compiling a C++14 code is as simple as:

g++-5.2.0 -std=c++14 file_name.cpp -o file_name:

If you need more help leave me a comment at:

[https://solarianprogrammer.com/2015/05/01/compiling-gcc-5-mac-os-x/](https://solarianprogrammer.com/2015/05/01/compiling-gcc-5-mac-os-x/)
