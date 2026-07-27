### https://github.com/KittyKatCoding/Lesson5
### $Lessonㅤ5:ㅤCreateㅤYourㅤNetworkㅤDocs$
### $Assignment:ㅤHomeㅤNetworkㅤDocumentation$
### $July⠀27,⠀2026⠀⠀Evan⠀W.$
### ⠀⠀⠀
# Evan W's Home Network Documentation
### ⠀⠀⠀
# Physical Network Topology
![Physical Topology](https://raw.githubusercontent.com/KittyKatCoding/Lesson5/refs/heads/main/000%20Physical%20Topology.webp)
# Logical Network Topology
![Physical Topology](https://raw.githubusercontent.com/KittyKatCoding/Lesson5/refs/heads/main/000%20Logical%20Topology.webp)

# IP Addressing And Subnet Information
The default gateway is 192.168.0.1 and the subnet is 255.255.255.0
The ip addresses are assigned by the AXE5400 Tr-Band Wi-Fi 6E Router DHCP Server
The Brother Printer has a reserved IP address of 192.168.0.113
### IP Addresses of Connected Client Devices
| Device Info | Interface |
| :--- | :---: |
| **BRNxxxxxxxxxxxx**<br>192.168.0.113 | Wired |
| **Agnes-PC**<br>192.168.0.53 | Wired |
| **EvanLaptop**<br>192.168.0.162 | Wi-Fi |
| **HS103 Kasa Smart Plug**<br>192.168.0.108 | Wi-Fi |
| **HS103 Kasa Smart Plug**<br>192.168.0.219 | Wi-Fi |
| **HS103 Kasa Smart Plug**<br>192.168.0.18 | Wi-Fi |
| **HS103 Kasa Smart PLug**<br>192.168.0.161 | Wi-Fi |
| **Pixel-3a**<br>192.168.0.73 | Wi-Fi |
| **Pixel-8**<br>192.168.0.87 | Wi-Fi |
| **Pixel-9a**<br>192.168.0.124 | Wi-Fi |
| **iPhone**<br>192.168.0.56 | Wi-Fi |
| **iPhone**<br>192.168.0.243 | Wi-Fi |

![Printer](https://raw.githubusercontent.com/KittyKatCoding/Lesson5/refs/heads/main/67.webp)
### The printer did not show up on the Wi-Fi Router's Connected Clients page, but i can ping it and print to it.
![Image 4](https://raw.githubusercontent.com/KittyKatCoding/Lesson5/main/4.png)
![Image 12](https://raw.githubusercontent.com/KittyKatCoding/Lesson5/main/12.png)
### Access Control List
The Brother printer is denied access to the internet, it only is allowed access to the local internet.  This is to stop the printer from getting updates.  The printer has generic toner and may reject the toner if the firmware is updated.
![Image 5](https://raw.githubusercontent.com/KittyKatCoding/Lesson5/main/5.png)
# Network Device Inventory

| Manufacturer | Device Name | Function |
| :--- | :--- | :--- |
| MikroTik | Fiber-to-Copper Converter | SFP to Ethernet conversion |
| TP-Link | AXE5400 Tri-Band Wi-Fi 6E Router | Home Wifi Router |

# Revision History
| Version | Date | Amendment | Author |
| :--- | :--- | :--- | :--- |
| 1.0 | July 27, 2026 | Initial release | Evan W |

# I do not have any servers, the only server is my Wi-Fi router's DHCP server for assigning ip addresses.
# The brother printer has a built in Web Server for configurations and a print server for printing.
![Image 10](https://raw.githubusercontent.com/KittyKatCoding/Lesson5/main/10.png)
My internet connection from Valley FIber is a Dynamic IP address.  Valler Viber's DHCP server has a lease time of 1200 seconds, which is 20 minutes.  Every 10 minutes the router requests to extend the IP Lease

![DHCP From Valley Fiber](https://raw.githubusercontent.com/KittyKatCoding/Lesson5/refs/heads/main/6767.webp)

The
