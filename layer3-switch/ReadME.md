# Layer 3 Switch

## 📌 Overview
Inter-VLAN routing is handled directly by the switch using SVIs.

## ⚙️ Configuration (Example)


interface vlan 10
ip address 192.168.1.1 255.255.255.0

interface vlan 20
ip address 192.168.2.1 255.255.255.0

interface vlan 30
ip address 192.168.3.1 255.255.255.0

ip routing


## 📸 Topology
![Topology](./topology.png)

## 📸 Configuration
![Config](./config.png)

## 📸 Test
![Test](./test.png)
