# pyYASDI
Python Wrapper for SMA YASDI C Library 

This is based on https://github.com/joachimlindborg/yasdiXMPP

pyYASDI provides a Python3 wrapper for the SMA YASDI C software to read data from SMA Converters.
Source: https://www.sma.de/produkte/apps-software/yasdi

Detailled information on YASDI with downloads, technical details and tutorials: https://www.heiko-pruessing.de/projects/yasdi/

The File libyasdiarmhf.tar contains the YASDI libraries compiled for ARM devices (Raspberry Pi), extract that to your library path (e.g. /usr/local/lib ). 

Please edit the yasdi.ini as needed and edit the paths of yasdi.ini and the YASDI libraries on your system in yasdiwrapper.py as needed.

Import yasdiwrapper.py in your python software

Tested with Python 2.7 and Python 3
