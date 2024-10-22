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

![WhatsApp Image 2024-10-20 at 22 01 49_2bf8a9ff](https://github.com/user-attachments/assets/bf1c37c0-9bf8-48b7-83df-025b1c570a91)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:



 dsniff:


![VirtualBox_JOHNYDJ_22_10_2024_21_37_25](https://github.com/user-attachments/assets/26852c00-ff0f-42ce-866f-2fb81426773b)




In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![WhatsApp Image 2024-10-22 at 21 39 33_33c4db4b](https://github.com/user-attachments/assets/a6930f1a-0a66-4e5e-b509-d9448a624bca)






In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![arspoof](https://github.com/user-attachments/assets/f3357943-7c86-447a-aa36-19f31e49638f)



Invoke the wireshark and examine the various menus  and controls of the tool:


![WhatsApp Image 2024-10-22 at 21 39 34_5e900c36](https://github.com/user-attachments/assets/b725cf86-2edd-40fe-b031-2a1cc34ae086)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
