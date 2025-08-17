# NMAP-scanning-project
This project is focused on identifying devices in a network , checking for vulnerabilities and uncovering open ports.

### Step One - Find your Network Range ### 
To scan our device (host) for open ports , we need to identify its IP address 
### Procedures ###


* Start NMAP from the CMD terminal
* type "ipconfig". This will display all IP addresses : select the interface you are using . In this case, the wireless interface


  <img width="942" height="456" alt="image" src="https://github.com/user-attachments/assets/a1081dcb-92a7-476d-876d-6ff5ccd0757c" />


### Step Two - Discovering Devices on the Network  ###
To discover the devices on the network and determine all the IP addresses that are currently connected to the same network (subnet) . Type Nmap -sn 10.74.167.0/24. Since the IP host is 10.74.167.149, then the network is 10.74.167.0


<img width="969" height="175" alt="image" src="https://github.com/user-attachments/assets/c7ed0437-e8b3-4427-b3a5-4814395804c2" />




