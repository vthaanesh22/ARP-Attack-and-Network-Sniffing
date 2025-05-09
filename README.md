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
![image](https://github.com/user-attachments/assets/a9f5dc56-856a-4b54-89c9-627f9cf31d82)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/user-attachments/assets/baba372c-a591-45b3-be8d-6cf753bf1f31)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/48f41c0c-f6a6-465e-8179-44f5def35bd6)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:


![image](https://github.com/user-attachments/assets/fddb424e-d901-4dbc-b0ef-61055ab0e624)

Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/user-attachments/assets/cbcfd0ef-9861-4f1e-b527-c081067405fe)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
