# nsoENG
***********************************************
NSO.py  Night Sky Objects

Program made in Python 3.7 to check daily visibility of stars at Slooh Observatories in Canary Islands and in Chile.

Required files:
================
1. NSO.py program 
2. ObjectData.csv: comma separated values -file of the celestial coordinates (Right Angle and Declination) of the objects. You can add your own customised data in the file if you choose
3. Observatory.csv: file of the observatory coordinates (name, longitude, latitude, starting and ending times for the observatory
4. Example.jpg: starting screen, can be omitted, you just don't see any graph in the beginning

Running the program:
====================
Start NSO.py with your python platform
- choose the object and observatory
- if you wish to save the graph, change the status of the check box. The file name will include the name of the object, the name of the observatory and the date.
- Due to the program structure, the no save option will save the graph as 'no_save.jpg'

Python modules:
===============
The Python modules are all usually within Python 3.7 environment, but might needed to be installed. 
- panda
- matplotlib
- pyqt5
- math
- datetime
- re
- csv

Version history:
================
Ver 1.2 10.06.2020
- added Messier, Caldwell and Variable Stars combobox

Ver 1.1 03.06.2020
- added the choice of saving the image
- corrected the date explanation on x-axis

Ver 1.0 30.5.2020
- first version


Credits:
========
Astronomical calculations based on Paul Schlyter's web site https://stjarnhimlen.se/comp/ppcomp.html
Inspiration from Jarmo Ruuth's web site https://ruuth.xyz/AstroMosaic.html
