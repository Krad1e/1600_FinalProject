# Converting to GPT is a multi-step process. Follow instructions below to convert. 

## **Step 2:** 
Once you have verified you are using the MBR format, it's time to convert the disk.  
We will use a built in windows tool called MBR2GPT to convert the disk.
* Open the start menu, and type 'run'
* Type 'cmd' in 'run' and press 'OK'
* Type 'mbr2gpt /validate /allowfullos'
* Type 'MBR2GPT.EXE /convert /allowfullos'
* Allow the application to complete
* If you run into an error "Failed to update ReAgent.xml", don't worry, the conversion still completed. This means you have not gone into your BIOS and updated the boot mode from CSM to UEFI yet 
* Restart your computer, go into your bios, look for your boot configuration, and change it from the legacy CSM boot mode to UEFI boot mode. Consult your motherboard manufacturer for more information on how to change this setting (it differs from manufacturer, Asus is not the same as Gigabyte, etc.) 
* [Here is a **very** general guide for switching your BIOS from CSM to UEFI](https://www.youtube.com/watch?v=LlrnnEIEbxk)
* Reboot your computer after updating your BIOS settings.
* [Now go back to Step 1](/ConvertMbrToGpt.md) and verify that your hard disk is running the GPT format.
## Congratulations! Your computer is is now running the GPT format and is ready for the Windows 11 upgrade (assuming you have a trusted platform module built into your motherboard already.) 
![Image of drive with GPT partition style](https://i.imgur.com/SVla1I0.png)