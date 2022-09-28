# pyYASDI
Python Wrapper for SMA YASDI C Library 

This is based on https://github.com/joachimlindborg/yasdiXMPP

pyYASDI provides a Python3 wrapper for the SMA YASDI software to read data from SMA Converters.
Source: https://www.sma.de/produkte/apps-software/yasdi

Detailled information on YASDI and Download: https://www.heiko-pruessing.de/projects/yasdi/yasdi.php

Technical Details: 
* https://www.heiko-pruessing.de/projects/yasdi/yasdi_technical.php
* https://www.heiko-pruessing.de/projects/yasdi/yasdi-tutorial-c.html

libyasdiarmhk.tar contains the YASDI libraries compiled for ARM devices (Raspberry Pi).

Please edit the yasdi.ini as needed and edit the paths of yasdi.ini and the YASDI Libraries on your system in yasdiwrapper.py as needed.

Import yasdiwrapper.py in your python software

Tested with Python 2.7 and Python 3.5
