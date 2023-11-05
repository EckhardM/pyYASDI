# pyYASDI
Python Wrapper for SMA YASDI C Library 

<sup>This is based on https://github.com/joachimlindborg/yasdiXMPP</sup>

pyYASDI provides a Python3 wrapper for the SMA YASDI C software to read data from SMA Converters.

It uses SMA YASDI (see https://www.sma.de/en/products/apps-software/yasdi or in German https://www.sma.de/produkte/apps-software/yasdi).

Detailled information on YASDI with downloads, technical details and tutorials see https://www.heiko-pruessing.de/projects/yasdi/

Find the whole YASDI source code and documentation in the Folder "YASDI" so you can compile that software for your system.

To compile YASDI for your own system you will need gcc and cmake:
<code>
$Bash> unzip yasdi-1.8.1build9-src.zip -d YASDI
$Bash> cd YASDI/projects/generic-cmake
$Bash> mkdir build-gcc
$Bash> cd build-gcc
$Bash> cmake ..
$Bash> make
$Bash> sudo make install    
$Bash> sudo ldconfig
</CODE>

Please edit the file <b>yasdi.ini</b> as needed and test with <code>yasdishell yasdi.ini</code>!<br>
Edit the paths of yasdi.ini and the YASDI libraries on your system in <b>yasdiwrapper.py</b> as needed.<br>
Import yasdiwrapper.py into your python software.

Tested with Python 2.7 and Python 3
