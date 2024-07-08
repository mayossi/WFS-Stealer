# WFS Stealer

Lets say you are an attacker that pwned a victim's Windows box and you have a 
special intrest in scanned documents.
After taking some screenshots and watching your targets actions you found out he is using none
other than WFS.EXE to scan his documents.
So, what do you do? use WFS Stealer.

WFS Stealer is a DLL that when injected to Windows Fax & Scan process hooks certain functions that enable it to steal images of scanned documents, store them in another location, all without the user noticing anything.

A quick little demo of a POC version of the project in action is [available here!](https://youtu.be/HdC1e6Rpves?si=15ez4nDGZeyE9o3b)
WFS Stealer was developed as a plugin for my implant and c2 framework.

### WTF is WFS.EXE?

TL;DR - A faxing and scanning utility available from Vista to Windows 11.
 
Wikipedia: Windows Fax and Scan is an integrated faxing and scanning application introduced in Windows Vista and included in the Business, 
Enterprise, and Ultimate Windows Vista editions as the replacement for the Fax Console of Windows XP;
it is available in all versions of Windows 7, Windows 8, Windows 10 (x86/x64) and Windows 11 (x64), but not on ARM64 versions of Windows 10 and Windows 11.

Windows Fax and Scan supports sending and receiving faxes, faxing or emailing scanned documents, and forwarding faxes as email attachments.

![wfs](/assets/WFS.JPG)


### Disclaimer
This repository is for research and educational purposes only, use of this code/information is your responsibility.
I take no responsibility and/or liability for how you choose to use the code/information available here.
By using, copying, or distributing any part of this repository or information provided in it, you understand and agree to use it at your own risk and you hold full responsibility for your actions.
This repository does not promote any hacking-related activity.
