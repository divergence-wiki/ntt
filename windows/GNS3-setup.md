GNS3 setup for Windows users
----------------------------

GNS3
----

GNS3 is a free open source LAB virtualization application.  
We will be using GNS3 as a CLIENT to connect to a GNS3 SERVER hosted on campus.  

Download
--------

Download the GNS3 installer from the GNS3 github: https://github.com/GNS3/gns3-gui/releases

Download the all-in-one exe file version "2.2.49".

Direct Link: [https://github.com/GNS3/gns3-gui/releases/download/v2.2.45/GNS3-2.2.49-all-in-one.exe](https://github.com/GNS3/gns3-gui/releases/download/v2.2.49/GNS3-2.2.49-all-in-one.exe)

Install
-------

Before installing GNS3 you should install [Putty](https://github.com/divergence-wiki/ntt/blob/main/windows/Putty-setup.md).  

Run the install file, and accept the default install prompts, except where noted.

#1 Choose Components | Match this screenshot.

<img width="376" alt="image" src="https://user-images.githubusercontent.com/102036007/163692222-c1be812b-d2e4-422a-90d9-4758f05059af.png">

#2 Npcap | This prompt may appear in the background, behind another application. If the installation seems to have stopped or paused, the prompt is waiting on you to make a section. Select yes to install Npcap. If you already have Wireshark installed, Npcap will already be installed and you will get a prompt asking if you want to replace Npcap with an older version. If so, select no.

#3 Solarwinds Standard Toolset | Select no.

Accept defaults for any further prompts.

After the install completes GNS3 and the GNS3 WebClient pack will start.  
Close the WebClient pack window.  

Leave GNS3 open and move on to the next section.  

Post-Install GNS3 Configuration
-------------------------------

#Default Instructions
---------------------

The first thing you should see is a prompt for how GNS3 should run.   
We are running appliances on a remote server.  

Note: If you don't see this prompt, or you accidently closed it, skip to the #Manual Instructions section below.  

<img width="499" alt="image" src="https://user-images.githubusercontent.com/102036007/163692739-c40c3a95-845c-4ef7-a65b-518e147dd992.png">

Get the Host, User, and Password information from your instructor.  
Click next once you have filled out the server info.  

After applying the server settings, GNS3 will process the changes, it may seem like it's frozen, give it a minute, if it still seems stuck - close and reopen GNS3.  

<img width="500" alt="image" src="https://user-images.githubusercontent.com/102036007/163692766-9a43257c-c2de-41d9-b268-f3630067a289.png">


#Manual Instructions
--------------------

In GNS3 go to Preferences -> Server  

On the Main Server tab:  

Make sure Enable local server is unchecked  
Get the Host, User, and Password information from your instructor.  
Click Apply once you have filled out the server info.  

After applying the server settings, GNS3 will process the changes, it may seem like it's frozen, give it a minute, if it still seems stuck - close and reopen GNS3.  

<img width="982" alt="image" src="https://user-images.githubusercontent.com/102036007/163693339-d13ce69c-ce0a-4a50-8c68-2135bbee841f.png">


Putty
-----

If you have already installed [Putty](https://github.com/divergence-wiki/ntt/blob/main/windows/Putty-setup.md).  

In GNS3 go to Preferences -> General

On the Console applications tab:  
Select Putty normal standalone version
