# pyYASDI
Python Wrapper for SMA YASDI C Library 

<sub><sup>This is based on https://github.com/joachimlindborg/yasdiXMPP</sup></sub>

pyYASDI provides a Python3 wrapper for the SMA YASDI C software to read data from SMA Converters.

It uses SMA YASDI (see https://www.sma.de/en/products/apps-software/yasdi or in German https://www.sma.de/produkte/apps-software/yasdi)

Detailled information on YASDI with downloads, technical details and tutorials see https://www.heiko-pruessing.de/projects/yasdi/

The File libyasdiarmhf.tar contains the YASDI libraries compiled for ARM devices (Raspberry Pi, 32 bit), extract that to your library path (e.g. /usr/local/lib ). Find the whole YASDI source code and documentation in the Folder "YASDI", so you can compile that software for your system.

Please edit the yasdi.ini as needed and edit the paths of yasdi.ini and the YASDI libraries on your system in yasdiwrapper.py as needed.

Import yasdiwrapper.py into your python software

Tested with Python 2.7 and Python 3
