# MadcapFlareInstall_MacOs

Repository for installing Madcap Flare on MacOs platforms & Introduction Course materials

## Use this guide to: 
- Create a Windows 11 virtual machine from a fresh install on your MacOs system.
- Install Madcap Flare.
- Take the Madcap Software introduction course. 

## Obtain Windows

The easiest way to obtain a Windows installer ISO is with the CrystalFetch app on macOS, a free utility for legally obtaining the newest Windows builds from Microsoft. These directions are a modified version of those found on the UTM website: https://docs.getutm.app/guides/windows/

## Instructions

### UTM Install
1. Navigate to the UTM website: https://mac.getutm.app/
2. Download the latest edition for your device model.

### CrystalFetch & ISO
1. Navigate to the mac App Store and download the lates version of the CrystalFetch ISO Downloader: https://apps.apple.com/us/app/crystalfetch-iso-downloader/id6454431289?mt=12
2. Open the App and select:
   - Version: Windows 11
   - Build: Latest
   - Architecture: Apple Silicon
   - Language: English
   - Edition: Windows 11
3. Click **Download**.
4. You still need a Windows product key but can find generic ones for free online. I recommend using Github, for example: https://gist.github.com/rvrsh3ll/0810c6ed60e44cf7932e4fbae25880df

### Configure the VM
1. Open UTM and click the + button to open the VM creation wizard.
2. Click **Virtualize**.
3. Click **Windows**.
4. Pick the amount of RAM and CPU cores you wish to give access to the VM. I recommend that you select whatever the default value is unless otherwise specified here. 
5. Click **Continue**.
6. Select **Install Windows 10 or higher**. 
7. Select **Install drivers and SPICE tools**. 
8. Click **Browse** and select the ISO you built with CrystalFetch.
9. Specify the maximum amount of drive space to allocate and click **Continue**.
 > Note: If you have a directory you want to mount in the VM, you can select it here. Alternatively, you can skip this and select the directory later from the VM window's toolbar. The shared directory will be available after installing SPICE tools. Click **Continue**.
10. Click **Save** to create the VM. 
11. Wait for the guest tools to finish downloading and click **Run** to start the VM.
12. Press any key to start the Windows installer and follow the instructions on screen. If you have issues with the mouse, press the mouse capture button in the toolbar to send mouse input directly. Press Control+Option together to exit mouse capture mode. Sometimes, due to driver issues, you can enter and exit capture mode and the mouse cursor works normally again.

  > Note: It may take the installer a while to finish and the virtual machine may restart several times to complete the installation. 

### Install MadcapFlare
1. Navigate to the MadcapFlare website and create a profile. For the "Please tell us the following so we can better serve your needs:" option, select: **I am current job seeker that needs Madcap Software experience**.
2. Click **Download MadcapFlare 2025 R2**.
   > Note: This is a larger file and may take a while to download. 

## Madcap Introductory Tutorial

During the download, I recommend that you download the tutorial materials from this repo in the Course Materials folder. The contents are:
- Madcap Introductory Documentation
- MadcapFlare Intro Training Guide
- Flare Intro Training materials "cities".
- MadCap Flare Intro Training Outline

  Navigate to the **Take the self-guided introductory course** and either view the embedded video on their site, or download each video on your device. When I did this there were 6 videos that covered 9 sections of the course. This may be different by the time you are reading this.

These Tutorials include basic navigation and function of the Madcap Flare product and include:
- Creating variables
- Creating Templates
- Using multimedia
- Inserting Snippets
- Tagging draft text
- Selecting publication targets
- How to invite SMEs for document review
