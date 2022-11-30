# Converting to GPT is a multi-step process. Follow instructions below to convert. 

## **Step 1: Verify that your hard disk is formatted in MBR.**
* Open the start menu, and type 'run'
* In 'run', type 'diskmgmt.msc' and press 'OK'
* In Disk Management, observe your Disks listed. Look for the one that has your operating system installed on it. For example, mine is _Disk 0_
* Right click on the far left box that displays your Disk number, so in my case, I right click on 'Disk 0' 
![Area to click is highlighted in red](https://i.imgur.com/F14C8bW.png)
* Click on 'Properties'
* Once you have opened 'Properties', move to the 'Volumes' tab
* Here you can verify your hard disks format type. Under 'Disk Information' 4 lines down, you will see 'Partition style'
* Verify that you are still running the legacy MBR partition style  
![Image of Volumes tab with MBR](https://learn.microsoft.com/en-us/windows/deployment/images/mbr2gpt-volume.png)  
**Note: If it says GPT, you are good to go, and can disgard the rest of this tutorial**
# </br>[Link to Step 2](/ConvertStep2.md)