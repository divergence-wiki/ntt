FortiClient setup for Mac users
-------------------------------


FortiClient VPN
---------------

FortiClient VPN is a free VPN client from FortiNet.  
We will use FortiClient to establish a split tunnel VPN to the Lab environment.  
Traffic for the LAB environment will flow over the VPN tunnel, all other traffic will flow over your normal network connection.  

Download
--------

Download the FortiClient VPN installer from the FortiNet website: https://www.fortinet.com/support/product-downloads#vpn

There are multiple FortiClient products, make sure to select "FortiClient VPN only".

Direct Link: https://links.fortinet.com/forticlient/mac/vpnagent

Install
-------

Run the install file, and accept the default install prompts.  
You do not need to make any changes during the install.  

Post-Install VPN Configuration
------------------------------

On macOS 11 Big Sur and 10.15 Catalina, after installing the VPN you will need to grant full disk access to fctservctl and FortiClient, as described in FortiNet's [documentation](https://docs.fortinet.com/document/forticlient/7.0.1/macos-release-notes/223986/special-notices).

> You can install FortiClient (macOS) 7.0.1 on macOS 11 Big Sur and 10.15 Catalina. With these releases, FortiClient works properly only when you grant permissions to access the full disk in the Security & Privacy pane for the following services:

...

> If you are using the VPN-only client, you only need to grant permissions for fctservctl and FortiClient.

Open FortiClient VPN and check the acknowledgement checkbox at the bottom, then I accept.

Click Configure VPN

Connection Name and Description are up to you. You can put whatever you want, it doesn't matter, just not blank.  
Get the Remote Gateway, Custom Port, and Username info from your instructor.  
Make sure to select the checkbox for Customize port.

Once you have filled out the connection info, click Save.

If you have already activated your FortiToken [Android](https://github.com/divergence-wiki/ntt/tree/main/android) | [iOS](https://github.com/divergence-wiki/ntt/tree/main/iOS), you are ready to connect to the VPN. Go ahead and test the VPN connection. When you connect it will prompt for the MFA token code from the FortiToken app.  

<img width="442" alt="image" src="https://user-images.githubusercontent.com/102036007/163693970-0b44d842-87e7-46b9-903b-6b1ee494d708.png">

