# F9P_RAWX_Logger_OLED
A GPS-RTK2 Board which incorporates the u-blox ZED-F9P dual band (L1 + L2) GNSS receiver. This Sky Horse fork allows for an OLED screen display to visualize the GNSS activity sent from the guide on how to assemble a GNSS PPK RAWX Logger from an Adafruit Feather M0 Adalogger and a SparkFun  Adalogger and F9P uBlox module, including showing the filename of the log file.

The RAWX files logged by this project can be processed using rtklibexplorer's version of RTKLIB

SOFTWARE.md describes how to install the Arduino IDE and all the libraries you will need for this project

HARDWARE.md describes how to connect the Adalogger to the SparkFun GPS-RTK2 board

UBX.md describes how the Arduino code communicates with the F9P using the u-blox UBX binary protocol to enable and log the RAWX messages

The Arduino directory contains the Arduino code.
