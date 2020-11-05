OPC-UA-Client-Addon
========================

### Description ###

The OPC UA Client Addon supports connecting to any OPC UA server from Windows or Pharlap. It supports auto-discovery of tags for easy configuration as well as CSV import for offline configuration. It supports all data types and arrays of data types except strings. You can set up any number of poll rates for groups of channels. This allows for slow updates on the majority of tags with quick updates on critical tags. Read, write, and read/write tags are supported. Basic status information is also provided for the tag quality and OPC connection.

### Help ###

Help is included in most System Explorer sections.

### Built Availability ###

https://github.com/NIVeriStandAdd-Ons/OPC-UA-Client-Custom-Device/releases

### Built Dependencies ###

OPC UA Driver

### Quality, Limitations ###

IP has been tested by developer. It meets VeriStand addon coding best practices. It is currently used by various customers.

String and String Array data types are not supported.  All other items are supported.

### Source Version ###

LabVIEW 2019

### Source Dependencies ###

LabVIEW RT 19.0

NI Veristand Custom Device Development Tools (https://github.com/ni/niveristand-custom-device-development-tools/releases)

OpenG Array Library 4.1.1.14

NI Asynchronous Messaging Communication Library 3.3.1.22 or later

### License ###

*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*
