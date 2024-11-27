
# ☕ Cafe Network Setup Simulation

Welcome to the **Cafe Network Setup Simulation**!! This project is a simulated network setup designed in **Cisco Packet Tracer** for a cafe environment, equipped with both wired and wireless connections for seamless customer service and efficient network management. 

## 📜 Project Overview

This network setup provides a realistic simulation of a small cafe's IT infrastructure, including devices for customer ordering, administration, and web hosting. The network utilizes **wireless connectivity** for customer-facing devices and **wired connections** for servers and control systems.

### 💡 Key Features
- **Dynamic IP Addressing**: Automatic IP assignment using DHCP
- **Domain Name Service (DNS)**: Simplifies access to the cafe’s website
- **Web Hosting**: Hosts the cafe's ordering system on an internal web server
- **Wireless Access Point**: Connects tablets for customer ordering and other wireless devices

## 🌐 Network Topology

| Component              | Description                                     |
|------------------------|-------------------------------------------------|
| **Servers**            | DNS, DHCP, and Web Server                       |
| **Switch**             | 2960 24TT, connecting wired devices             |
| **Access Point**       | `CafeWiFi` (SSID: CAFE-CONNECT) for wireless devices |
| **Tablets (x6)**       | Wireless tablets for customer order placement   |
| **Administrator PC**   | Central computer for order and network management |
| **Laptop**             | Additional wireless device for network monitoring |

---

### 📊 Network Diagram

The **Network Diagram** showcases the setup, including the placement of servers, switches, and access points. Devices are connected via a centralized switch and a secure wireless access point for easy access across the cafe.

## 📋 Configuration Details

| Device                  | IP Address         | Role                                      |
|-------------------------|--------------------|-------------------------------------------|
| **DNS Server**          | 192.168.1.22      | Resolves domain `www.cafe.com`            |
| **DHCP Server**         | 192.168.1.21      | Provides IP addresses dynamically         |
| **Web Server**          | 192.168.1.20      | Hosts cafe ordering system                |
| **Access Point (Gateway)** | 192.168.1.1   | Connects wireless devices via `CAFE-CONNECT` |

---

## 🛠 Configuration Steps

Follow these steps to configure each component in Cisco Packet Tracer:

1. **DNS Server** 🖥️
   - **IP**: `192.168.1.22`
   - **Domain**: Map `www.cafe.com` to Web Server IP.

2. **DHCP Server** 🔄
   - **IP**: `192.168.1.21`
   - **Range**: `192.168.1.50` - `192.168.1.100`
   - **Default Gateway**: `192.168.1.1`
   - **DNS**: `192.168.1.22`

3. **Web Server** 🌐
   - **IP**: `192.168.1.20`
   - **Service**: Hosts web-based ordering application.

4. **Switch** 🔗
   - Connects all servers, administrator PC, and access point.

5. **Access Point** 📡
   - **SSID**: `CAFE-CONNECT`
   - **IP**: `192.168.1.1`
   - **DHCP**: Disabled (relies on DHCP server)

6. **End Devices** 📲
   - Connect to **CAFE-CONNECT** network via DHCP for automatic IP configuration.

---

## 🎨 Visual Layout

- **Network Diagram**: Provides a visual of device interconnections.
- **Cafe Floor Layout**: Shows device locations in the cafe to ensure efficient workflow.

## 🚀 How It Works

1. **Customer Ordering** 🛒: Customers use tablets connected to **CAFE-CONNECT** to place orders through the web application.
2. **Network Management** 🔍: The Administrator PC manages orders, monitors network performance, and troubleshoots as needed.
3. **Web Access** 🌐: Devices access the cafe’s ordering system through `www.cafe.com`.

---

## 📂 Project Requirements

- **Cisco Packet Tracer**: Version 8.0 or higher recommended to open and run the network simulation file.

---

## 📸 Screenshots

![Network Diagram]![image](https://github.com/user-attachments/assets/e5d33b95-4786-48aa-912b-780fc1291fe8)
![Cafe Layout]![image](https://github.com/user-attachments/assets/89fc55e3-ef77-42e4-b623-d961f10410b6)
![browser window]![image](https://github.com/user-attachments/assets/76854fc3-46dc-4355-9541-23ed030a1671)


---
## 🌟 Contributors

A big thank you to everyone who helped bring this project to life!

<div style="display: flex; gap: 10px;">

[![AKdevi99](https://img.shields.io/badge/GitHub-AKdevi99-6f42c1?style=for-the-badge&logo=github&logoColor=white&labelColor=black)](https://github.com/AKdevi99)
[![Apekshajawali](https://img.shields.io/badge/GitHub-Apekshajawali-6f42c1?style=for-the-badge&logo=github&logoColor=white&labelColor=black)](https://github.com/Apekshajawali)

</div>

---

💙 Interested in contributing? Feel free to make a PR or contact us!


## 📜 License

This project is licensed under the **MIT License**. Feel free to use and modify the simulation for educational or personal purposes.

## 🙏 Acknowledgments

Special thanks to **Cisco** for providing Packet Tracer as an essential tool for network simulation.

---

**Enjoy managing your very own cafe network simulation!** ☕
