# Networking Commands

## 1. ipconfig

Purpose:
Displays the current network configuration of a Windows system.

Command:

ipconfig

<img width="460" height="497" alt="ipconfig" src="https://github.com/user-attachments/assets/d728c25b-cabf-43ab-ba78-5526b6b9fcb0" />

Observations:

* Displays IPv4 address.
* Displays subnet mask.
* Displays default gateway.

---

## 2. ping

Purpose:
Tests connectivity between the local machine and a remote host.

Command:

ping google.com

<img width="344" height="137" alt="Screenshot 2026-06-19 175239" src="https://github.com/user-attachments/assets/8d4ad6c5-259d-4026-8448-a20ad21fddf2" />

Observations:

* Replies received successfully.
* Shows network latency.
* Confirms internet connectivity.

---

## 3. nslookup

Purpose:
Retrieves DNS information for a domain.

Command:

nslookup google.com

<img width="234" height="96" alt="nslookup" src="https://github.com/user-attachments/assets/a03e0165-d7c4-46f6-b76d-86ce8814a827" />

Observations:

* DNS server responded successfully.
* Domain name resolved to an IP address.

---

## 4. tracert

Purpose:
Shows the path packets take to reach a destination.

Command:

tracert google.com

<img width="602" height="155" alt="tracert" src="https://github.com/user-attachments/assets/3c465692-4d1f-49b3-a11c-479f2f322f0d" />

Observations:

* Multiple network hops observed.
* Destination reached successfully.

---

## 5. arp

Purpose:
Displays the ARP cache.

Command:

arp -a

<img width="391" height="338" alt="arp -a" src="https://github.com/user-attachments/assets/5039a24f-7a69-4b6a-a203-7915e05fc364" />

Observations:

* Lists IP-to-MAC address mappings.
* Useful for troubleshooting local networks.

---

## 6. netstat

Purpose:
Displays active network connections and listening ports.

Command:

netstat -ano

<img width="449" height="356" alt="Screenshot 2026-06-19 180921" src="https://github.com/user-attachments/assets/bd1cd376-f6e8-4323-832e-fc72040b5f82" />

Observations:

* Shows active connections.
* Displays associated process IDs.
* Useful for identifying suspicious connections.
