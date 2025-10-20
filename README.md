# MadcapFlareInstall_MacOs
Repository for installing Madcap Flare on MacOs platforms &amp; Introduction Course materials

Use this guide to: c
Create a Windows 11 virtual machine from a fresh install on your MacOs system.
Install Madcap Flare.
Take the Madcap Software introduction course. 

Obtain Windows
The easiest way to obtain a Windows installer ISO is with the  CrystalFetch app on macOS, a free utility for legally obtaining the newest Windows builds from Microsoft.
These directions are a modified version those found on the UTM website: https://docs.getutm.app/guides/windows/



Instructions
H2 UTM
Navigate to the UTM website and download the latest edition for your device model.

H2 CrystalFetch & ISO
Navigate to the mac App Store and download the lates version of the CrystalFetch ISO Downloader.
    https://apps.apple.com/us/app/crystalfetch-iso-downloader/id6454431289?mt=12
Open the App and select:
    vVrsion: Windows 11
    Build: Latest
    Architecture: Apple Silicon
    Language: English
    Edition: Windows 11
Click <Strong>Download<Strong>
You still need a Windows product key but can find generic ones online. I recommend using Github, for example: https://gist.github.com/rvrsh3ll/0810c6ed60e44cf7932e4fbae25880df

H2 Configure the VM
Open UTM and click the <strong>+<strong> button to open the VM creation wizard.
Click <strong>Virtualize<strong>.
Click <strong>Windows<strong>.
Pick the amount of RAM and CPU cores you wish to give access to the VM. I recommend that you select whatever the default value is unless otherwise specified here. 
Click <strong>Continue<strong>.
Select <strong>Install Windows 10 or higher<strong> . 
Select <strong>Install drivers and SPICE tools<strong>. 
Click <strong>Browse<strong> and select the ISO you built in step 2-3.
Specify the maximum amount of drive space to allocate and click <strong>Continue<strong>.
    <strong>Note<strong>: If you have a directory you want to mount in the VM, you can select it here. Alternatively, you can skip this and select the directory later from the VM window’s toolbar. The shared directory will be available after installing SPICE tools (see below). Click <strong>Continue<strong>.
Click <strong>Save<strong> to create the VM. 
    Wait for the guest tools to finish downloading and click <strong>Run<strong> to start the VM.
Press any key to start the Windows installer and follow the instructions on screen. If you have issues with the mouse, press the mouse capture button in the toolbar to send mouse input directly. Press Control+Option together to exit mouse capture mode. Sometimes, due to driver issues, you can enter and exit capture mode and the mouse cursor works normally again.
    <strong>Note<strong>: It may take the installer a while to finish and the virtual machine may restart several times to complete the installation. 

H2 Install MadcapFlare
Navigate to the MadcapFlare website and create a profile. For the <strong>Please tell us the following so we can better serve your needs:<Strong> option, select: <Strong>I am current job seeker that needs Madcap Software experience.<Strong>
Click <Strong>Download MadcapFlare 2025 R2<Strong>
    <Strong>Note<Strong>: This is a larger file and may take a while to download. 

H3 Madcap Introductory Tutorial
During the download, I recommend that you download the tutorial materials from this repo in the <Strong>Course Materials<Strong> folder. The contents are:
<li>Madcap Introductory Documentation
MadcapFlare Intro Training Guide
Madcap Video Tutorial 1 & 2
Madcap Video Tutorial 3 & 4
Madcap Video Tutorial 5
Madcap Video Tutorial 6
Madcap Video Tutorial 7
Madcap Video Tutorial 8 & 9<li>

These Tutorials include basic navigation and function of the Madcap Flare product and include:
<li>Creating variables
Creating Templates
Using multimedia
Inserting Snippets
Tagging draft text
Selecting publication targets
How to invite SMEs for document review<li>
