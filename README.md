﻿# Mifare Windows Tool - MWT 
 ![MWT_small](https://user-images.githubusercontent.com/3501675/73345370-3cb78d80-4284-11ea-8c17-e67fa8b54adc.png)
 
### This is a Windows NFC-App for reading, writing, analyzing, etc. MIFARE® Classic RFID-Tags

#### GENERAL INFORMATION

This tool provides several features to interact with MIFARE Classic RFID-Tags with ACR122U tag reader.

It is designed for users who have at least basic familiarity with the MIFARE Classic technology.

More information in <a href="https://github.com/xavave/Mifare-Windows-Tool/wiki">WIKI<a/> 

#### PREREQUISITES

- An ACR122U Tag Reader
- Installed drivers (Native + LibusbK) : documentation here : http://legacy.averbouch.biz/libnfc-and-nfc-utils-binaries-on-windows-10/

#### INSTALLATION

Windows x64 : With MSI Setup provided here : https://github.com/xavave/Mifare-Windows-Tool/releases  
 
#### IMPORTANT NOTES

Some important things are:

- The features this tool provides are very basic.

- The first block of the first sector of an original
MIFARE Classic tag is read-only i.e. not writable. But there
are special MIFARE Classic tags that support writing to the
manufacturer block with a simple write command. This App is able to
write to such tags and can therefore create fully correct clones.

- However, some special tags require a special command sequence
to put them into the state where writing to the manufacturer block is possible.
These tags will not work.

- Remember this when you are shopping for special tags!

#### IF YOU ENCOUNTER A PROBLEM PLEASE REPORT IT <a href="https://github.com/xavave/Mifare-Windows-Tool/issues">HERE</a> 

<img src="https://user-images.githubusercontent.com/3501675/73281623-8c4c7980-41f0-11ea-967b-f649b0147f0a.png" width="300" height="auto" />
 
<img src="https://user-images.githubusercontent.com/3501675/73309783-3f35cb00-4223-11ea-9df6-73375f301b28.png" width="600" height="auto" /> 

![image](https://user-images.githubusercontent.com/3501675/73364730-57e9c380-42ab-11ea-8a4c-31f3b0dace5c.png)

<img src="https://user-images.githubusercontent.com/3501675/73280408-c3219000-41ee-11ea-8e17-c7e6b5b952b8.png" width="300" height="auto" /> 
 <img src="https://user-images.githubusercontent.com/3501675/73311455-b91b8380-4226-11ea-8ff7-c53153d2ab51.png" width="600" height="auto" />  

