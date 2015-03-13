## Data Dashboard Custom Device ##

**Data Dashboard Custom Device**  allows users to publish NI VeriStand channels as LabVIEW shared variables. User can connect to the published shared variables e.g. using the [Data Dashboard for LabVIEW](https://decibel.ni.com/content/docs/DOC-19387).

### LabVIEW Version ###

LabVIEW 2013

To build the custom device in higher versions of LabVIEW open the Select Channels Dialog.vi, right click the .NET Control in the front panel -> "Select .NET Control" -> Choose "NationalInstruments.VeriStand.SystemStorageUI" as Assembly and "TreeBrowserWF" under "Controls". Inthe dialog that pops up hit "ignore".
Also follow the Readme.txt in /Source/LV_utilities.zip

### Built Availability ###

Builds of this IP are not available.

### Quality, Limitations ###

This IP was made in 2014 and has not been tested since. There are no known users of the IP. Proceed with caution.

### Dependencies ###
[DSC Module](http://www.ni.com/labview/labviewdsc/)


### Quality, Limitations ###

This IP should be considered high quality and mature. The IP has been used worldwide by many customers in deployed applications.

### Dependencies ###

- The packed library build from [Scan Engine Custom Device Classes](https://github.com/NIVeriStandAdd-Ons/Scan-Engine-Custom-Device-Classes).
- The FXP build from [Scan Engine Custom Device FXP LLB](https://github.com/NIVeriStandAdd-Ons/Scan-Engine-Custom-Device-FXP-LLB).
- NI Industrial Communications for EtherCAT
- NI RIO

### License ###

*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*