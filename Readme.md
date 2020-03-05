Data-Publishing-Service
========================

### Description ###

**Data Publishing Service** allows users to publish NI VeriStand channels and Alarms status as SystemLink tags. User can connect to the tags via SystemLink. The service will attempt to publish the channels that were configured as Aliases in the System Definition File. 

After running for the first time, the service will automatically generate a file called Data Publishing Service.ini that can be used to configure the behavior of the service.

* Library.Name: Configures the namespace for the data that will be published by this service.

* Alias.FolderPath: By default set to ALL which means the service will publish all of the channels configured as Aliases. Use a specific folder name in case you want to filter the data that gets sent.

* Publish.Period_ms: Configures the period used by the service to send updated tags to the server.

* Alias.Publish: If TRUE, the service will publish the Aliases channels as System Link double tags. If FALSE, the aliases channels are not published. 

* Alarm.Publish: If TRUE, the service will publish the status of VeriStand Alarms as System Link string tags. If FALSE, the status of the alarms are not published. 

* Tags.UndeployKill: If TRUE, the service will delete the created tags from the SystemLink server once undeployed. If FALSE, the service will just close the reference to the tags and keep them in the server. 

### Help ###

Help is included in most System Explorer sections.

### Built Availability ###

https://github.com/NIVeriStandAdd-Ons/Data-Publishing-Service/releases 

### Built Dependencies ###

[SystemLink](http://www.ni.com/en-us/shop/electronic-test-instrumentation/application-software-for-electronic-test-and-instrumentation-category/systemlink.html)

### Quality, Limitations ###

IP has been tested by developer. It meets VeriStand addon coding best practices.

### Source Version ###

LabVIEW 2019

### Source Dependencies ###
[SystemLink](http://www.ni.com/en-us/shop/electronic-test-instrumentation/application-software-for-electronic-test-and-instrumentation-category/systemlink.html)

### License ###

*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*