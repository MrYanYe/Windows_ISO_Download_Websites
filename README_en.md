# Windows_ISO_Download_Websites
Windows 8, 10, 11 ISO download websites (useful and clean). 

**Read this in other language: [Chinese(origin)](README.md).**


Win8, Win10, Win11 ISO file download websites. ISO download, ISO, system update, Windows Update, Microsoft. If you want to upgrade Windows by double-clicking the ISO file (no USB drive needed), note that Microsoft’s official site currently only provides the **multilingual** Windows 10 22H2 ISO, while most laptops sold in China come preinstalled with the **single-language** Windows 10 **Home China** edition — these are **two different editions**. The latter only allows Chinese as the display language. From what I found, the reason for this split seems to be that the Home China edition is priced lower than the multilingual international edition, so Microsoft specifically released this edition for mainland China.

So if you mount the multilingual ISO and run Setup, it will ask you to enter a product key during the process. If you don’t want to reactivate and want to keep the previously preinstalled Home China edition, use this website (as of 2025/12/06 it still works):

https://msdl.gravesoft.dev/#

Once there, click to download **Windows 10 22H2 Home China (19045.2006)** ```ID 2378```.

Of course, if you need other Windows ISO editions, this site also includes win8.1, win10, win10 Home China, win11, win11 pro, win11 Home China, win11 Pro Home China, and so on. I wrote this mainly because I needed the Win10 Home China ISO and found it on that site, but many people will have other needs.

---

The reason I needed this was that I uninstalled a Microsoft-developed app, PowerToys, and then found that fn+esc no longer toggled between volume keys and function keys. I went into the DELL BIOS to enable the fn+esc function, but after rebooting I discovered **Settings and the search box would crash as soon as they opened** — they wouldn’t stay open. Online suggestions said to repair with PowerShell, but PowerShell itself would also crash on open. I went to “Turn Windows features on or off,” unchecked and rechecked the PowerShell option, and then PowerShell finally worked. However, Settings and Search still wouldn’t open after a lot of troubleshooting, so I had to reinstall the system (without losing personal files — just reinstall or upgrade the OS).

I tried using Microsoft’s official MediaCreationTool to update, but for some reason the MediaCreationTool stayed at 0% on the download screen; I tried many fixes without success (my PC has had Windows Update issues for years — it always reported missing system components in Settings, so my Win10 stayed at version 1909; not sure if that’s related). That’s why I found this method of updating Win10 to 22H2 directly using an ISO file.


---
### After downloading the ISO file, follow Microsoft’s official instructions

https://www.microsoft.com/en-gb/software-download/windows10

https://www.microsoft.com/zh-cn/software-download/windows10

Other ways to use an ISO file to install Windows 10 (click to show detailed or brief info)

If you downloaded an ISO file for Windows 10, the file will be saved locally to the location you chose. If you have a third-party DVD burning program installed that you prefer to use to create an installation DVD, you can go to the location where the file is saved, double-click the ISO file to open that program, or right-click the ISO file, choose Open with, and then select your preferred DVD burning software.

If you want to use the Windows Disc Image Burner to create an installation DVD, go to the location where the ISO file is saved. Right-click the ISO file, then choose Properties. On the General tab, click Change, choose the program you want to use to open ISO files in File Explorer, and then choose Apply. After that, right-click the ISO file and choose Burn disc image.

If you want to install Windows 10 directly from the ISO file without using a DVD or flash drive, you can do so by mounting the ISO file. This will upgrade your current operating system to Windows 10.

To mount the ISO file, do the following:

Go to the location where the ISO file is saved, right-click the ISO file, and choose Properties.  
On the General tab, click Change…, choose the program you want to use to open ISO files in File Explorer, and then choose Apply.  
Right-click the ISO file, then choose Mount.  
Double-click the ISO file to view its contents. Double-click **setup.exe** to start the Windows 10 installer.

---


Note: If you want to keep your apps and files, be sure at the step after clicking setup.exe to **select Keep personal files and apps** — although this is the default option.

I also included a method to permanently disable Windows Update if you don’t want to receive Windows Update pushes.