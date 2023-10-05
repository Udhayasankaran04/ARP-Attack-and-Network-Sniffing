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
![image](https://github.com/Udhayasankaran04/ARP-Attack-and-Network-Sniffing/assets/119393933/c01350a2-280f-4a20-acc4-99b251cf2555)
From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>

## OUTPUT:
![image](https://github.com/Udhayasankaran04/ARP-Attack-and-Network-Sniffing/assets/119393933/15ff73f4-6d47-4c0c-bb7e-3698e758424e)

 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:
![image](https://github.com/Udhayasankaran04/ARP-Attack-and-Network-Sniffing/assets/119393933/8b02d9cb-ef7b-4a34-a450-6ff6734ee104)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/Udhayasankaran04/ARP-Attack-and-Network-Sniffing/assets/119393933/70b4832c-d296-4e02-a0ad-f707395640c2)

Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/Udhayasankaran04/ARP-Attack-and-Network-Sniffing/assets/119393933/c928c0d4-6c71-4aae-b32a-1ca6d105cb36)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
