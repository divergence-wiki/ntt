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


Your instructor will provide details on configuring the VPN.
