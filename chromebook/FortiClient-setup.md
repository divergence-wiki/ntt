
FortiClient setup for Chromebook users
--------------------------------------

FortiClient VPN
---------------

FortiClient VPN is a free VPN client from FortiNet.  
We will use FortiClient to establish a split tunnel VPN to the Lab environment.  
Traffic for the LAB environment will flow over the VPN tunnel, all other traffic will flow over your normal network connection.  

Download
--------

Download the FortiClient VPN app from the Google Play store: https://play.google.com/store/apps/details?id=com.fortinet.forticlient_vpn&hl=en_US&gl=US

Install
-------

Innstall the app from the Play Store.  
You do not need to make any changes during the install.  

Post-Install VPN Configuration
------------------------------

Open FortiClient VPN and check the acknowledgement checkbox at the bottom, then I accept.

Click Configure VPN

Connection Name and Description are up to you. You can put whatever you want, it doesn't matter, just not blank.  
Get the Remote Gateway, Custom Port, and Username info from your instructor.  
Make sure to select the checkbox for Customize port.

Once you have filled out the connection info, click Save.

If you have already activated your FortiToken [Android](https://github.com/divergence-wiki/ntt/tree/main/android) | [iOS](https://github.com/divergence-wiki/ntt/tree/main/iOS), you are ready to connect to the VPN. Go ahead and test the VPN connection. When you connect it will prompt for the MFA token code from the FortiToken app.  

<img width="442" alt="image" src="https://user-images.githubusercontent.com/102036007/163693970-0b44d842-87e7-46b9-903b-6b1ee494d708.png">
