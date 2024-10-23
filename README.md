### Date:
# Ex-4: ARP-Attack-and-Network-Sniffing
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
## ARP spoofing: 
A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![Screenshot 2024-10-23 083129](https://github.com/user-attachments/assets/42d9b536-23e4-4a72-90e6-11639c92283d)


</br>
From kali linux issue the command :
```
sudo arpspoof -i eth0 -t <target_system> <gateway>
```
 
## Output:
![Screenshot 2024-10-23 084610](https://github.com/user-attachments/assets/8c22e506-a760-4e2d-9b49-c59552b44061)


## dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## Output:

In Kali issue the following commands:
```
sudo dsniff
```

![Screenshot 2024-10-23 082857](https://github.com/user-attachments/assets/244b62f3-4bfe-4556-8970-b31a38ba514b)

## Output:

![Screenshot 2024-10-23 082751](https://github.com/user-attachments/assets/a0149a7e-70f3-44bd-9eea-70159c7fd35c)


## Wireshark:
Invoke the wireshark and examine the various menus  and controls of the tool:
## Output:
![Screenshot 2024-10-23 094305](https://github.com/user-attachments/assets/51d6ff17-1492-4f9b-b9f9-eefa4f2a91dd)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
