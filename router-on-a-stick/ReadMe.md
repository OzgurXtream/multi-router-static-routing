# Router on a Stick

## 📌 Overview
Inter-VLAN routing is achieved using a single physical interface with subinterfaces.

## ⚙️ Configuration (Example)


interface fa0/0.10
encapsulation dot1Q 10
ip address 192.168.1.1 255.255.255.0

interface fa0/0.20
encapsulation dot1Q 20
ip address 192.168.2.1 255.255.255.0


## 📸 Topology
![Topology](https://github.com/OzgurXtream/multi-router-network/blob/main/router-on-a-stick/Rons_Toplogy.png?raw=true)  

## 📸 Configuration
![Config](https://github.com/OzgurXtream/multi-router-network/blob/main/router-on-a-stick/Rons_Config.png?raw=true)

## 📸 Test
![Test](./test.png)
