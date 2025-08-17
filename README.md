# NMAP-scanning-project
This project is focused on identifying devices in a network , checking for vulnerabilities and uncovering open ports.

### Step One - Find your Network Range ### 
To scan our device (host) for open ports , we need to identify its IP address 
** Procedures **


* Start NMAP from the CMD terminal
* type "ipconfig". This will display all IP addresses : select the interface you are using . In this case, the wireless interface


  <img width="942" height="456" alt="image" src="https://github.com/user-attachments/assets/a1081dcb-92a7-476d-876d-6ff5ccd0757c" />


### Step Two - Discovering Devices on the Network  ###
To discover the devices on the network and determine all the IP addresses that are currently connected to the same network (subnet) . Type Nmap -sn 10.74.167.0/24. Since the IP host is 10.74.167.149, then the network is 10.74.167.0


<img width="969" height="175" alt="image" src="https://github.com/user-attachments/assets/c7ed0437-e8b3-4427-b3a5-4814395804c2" />


### Step Three - Scanning for Open Port ###
This step involves identifying open ports on the host machine that can lead to an attack or security breach 
** Procedures **


* Select any of the IP address in the network
* Use this map command to identify open ports (Nmap<HostIPAddress>).


<img width="864" height="177" alt="image" src="https://github.com/user-attachments/assets/5109f9a7-7784-48ad-89d5-f0f32602a58a" />

### Step Four - Identify Services ###
This step involes identifying services on the host machine (Target). To achieve this with Nmap , we used the following command : nmap -sV


<img width="941" height="200" alt="image" src="https://github.com/user-attachments/assets/fdf95fb9-4bb5-41a8-b9fc-779c8662a32b" />








