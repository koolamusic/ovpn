# An Open VPN script for Linux US/DE/UK/SG/NL

## Easy Connect to OpenVPN services From Linux Terminal

**Functions:**   
* Check for OpenVPN instalation and install
* Download popular free VPN service profiles
* Retrieve and extract password file from defined URLS
* Outbound port and port range tester – Firewall tester – with help of PORTQUIZ.NET
* Select downloaded free OpenVPN profile
* Connect to selected profile   
You can establish a VPN connection from Terminal refer to (help.txt) for instructions     



# Installation

* Open Terminal 
* git clone `https://github.com/tecmie/ovpn.git`    
* chmod +x ovpn/script.sh     
* run `bash ovpn/script.sh`
* In some distros you will have to run sript with `sudo` as you must be administrator to establish a connection


# Supported services   
* [VPNBook.com](www.VPNBook.com/) Please [donate](http://www.vpnbook.com/freevpn) to support this great free VPN service.
  * Supports P2P downloading (EURO1 and EURO2 servers) 
  * Multiple servers in diferent countries
  * Ports: TCP 80, TCP 443, UDP 53, UDP 25000     
* [VPNkeys.com](https://www.vpnkeys.com/) Please [donate](https://www.vpnkeys.com/get-free-vpn-instantly/) to support this great free VPN service.  
  * Multiple servers in diferent countries  
  * Ports: TCP 80, TCP 443, UDP 53, UDP 25000   


# Extend Country List 
- To extend this vpn you can create a premium account on any of the listed providers and export a config for any country of your choice


# ToDo
- Add support for external open vpn profiles
- Include option to input relative path for vpn profile


# Supported OS   
* Debian based Linux   
* RPM based distributions (not tested)   
This is executable bash script. You can try run it modified or as is on other Unix-like operating systems. (Linux/BSD/MacOSX/Solaris)    
