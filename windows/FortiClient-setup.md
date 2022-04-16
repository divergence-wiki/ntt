FortiClient setup for Windows users
-----------------------------------

FortiClient VPN
---------------

FortiClient VPN is a free VPN client from FortiNet.  
We will use FortiClient to establish a split tunnel VPN to the Lab environment.  
Traffic for the LAB environment will flow over the VPN tunnel, all other traffic will flow over your normal network connection.  

Download
--------

Download the FortiClient VPN installer from the FortiNet website: https://www.fortinet.com/support/product-downloads#vpn

There are multiple FortiClient products, make sure to select "FortiClient VPN only".

Direct Link: https://links.fortinet.com/forticlient/win/vpnagent

Install
-------

Run the install file, and accept the default install prompts.  
You do not need to make any changes during the install.  

Post-Install VPN Configuration
------------------------------

Open FortiClient VPN and check the acknowledgement checkbox at the bottom, then I accept.

Click Configure VPN

Connection Name and Description are up to you. You can put whatever you want, it doesn't matter, just not blank.  
Get the Remote Gateway, Custom Port, and Username info from your instructor.  
Make sure to select the checkbox for Customize port.

Once you have filled out the connection info, click Save.

If you have already activated your FortiToken [Android](https://github.com/divergence-wiki/ntt/tree/main/android) | [iOS](https://github.com/divergence-wiki/ntt/tree/main/iOS), you are ready to connect to the VPN. Go ahead and test the VPN connection.  

<img width="442" alt="image" src="https://user-images.githubusercontent.com/102036007/163693970-0b44d842-87e7-46b9-903b-6b1ee494d708.png">
