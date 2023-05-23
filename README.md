# fastscan
A quick bash script with an unoriginal name which can be used to enumerate open TCP ports on a host with masscan followed by an aggressive scan with Nmap on those target ports.

Usage:
```
IP=192.168.1.1
chmod +x fastscan
./fastscan $IP
```

Output files will named nmap_A_ports_$IP.txt, this can be modified on line 15.
