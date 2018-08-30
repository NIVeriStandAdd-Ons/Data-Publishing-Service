## Data Publishing Service##

**Data Publishing Service**  allows users to publish NI VeriStand channels as LabVIEW shared variables or as SystemLink tags. User can connect to the published shared variables e.g. using the [Data Dashboard for LabVIEW](https://decibel.ni.com/content/docs/DOC-19387) or the the tags via SystemLink. SystemLink is used by default. If the user wants to use DSC, you need to set the project property "DSC" to ENABLED and rebuild the service. Then make sure the ini file contains the Client = "DSC".

### LabVIEW Version ###

LabVIEW 2015

### Built Availability ###

Users are allowed to build anything under Build Specifications in the source's LabVIEW project(s).  Pre-built versions are available upon request through NI Field Sales. 

### Quality, Limitations ###

IP has been tested by developer. It meets VeriStand addon coding best practices.

### Dependencies ###
[DSC Module](http://www.ni.com/labview/labviewdsc/) (if using shared variables and Data Dashboard)
[SystemLink]

### License ###

*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*