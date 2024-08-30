# Networking
Using lpcap library create a sample program to find  ARP sniffing on the local Network.
Only works on linux based machines.
clone this  repo and compile the arp_sniff_detector.c file and run the executetable, its' start watching the ARP sniffing on your network.
Mandatory -> libpcap library , if it's not on your system please run this command: **sudo apt-get install libpcap-dev**
While compile the program, link  ths lpcap library like this  ** gcc -o arpdetector arp_sniff_detector.c -lpcap**
