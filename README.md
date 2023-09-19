# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:

![image](https://github.com/Vasanthpushpa/ARP-Attack-and-Network-Sniffing/assets/119291100/891ce98f-7226-4fe8-aa4b-8572866c77a7)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/Vasanthpushpa/ARP-Attack-and-Network-Sniffing/assets/119291100/59c8581e-1d3d-49c7-87b3-d5030eec377d)

 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/Vasanthpushpa/ARP-Attack-and-Network-Sniffing/assets/119291100/3dd7ba33-9298-4b36-87c8-62197b26ee5c)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/Vasanthpushpa/ARP-Attack-and-Network-Sniffing/assets/119291100/8eba83e2-c925-4d37-9ebe-275c8c5a539d)


Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/Vasanthpushpa/ARP-Attack-and-Network-Sniffing/assets/119291100/ccdb9adc-913d-4bee-b077-2a08e6134680)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
