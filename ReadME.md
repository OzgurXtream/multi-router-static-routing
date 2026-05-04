# VLAN & Inter-VLAN Routing

This project demonstrates how different VLANs can communicate using two different methods.

## 🔧 Methods

### 1️⃣ Router on a Stick
- Uses subinterfaces
- 802.1Q encapsulation
- Routing handled by router

### 2️⃣ Layer 3 Switch
- Uses SVI (interface vlan)
- Routing handled by switch

## 📊 Comparison

| Feature | Router on a Stick | Layer 3 Switch |
|--------|------------------|----------------|
| Performance | Medium | High |
| Scalability | Limited | Better |
| Real-world usage | Small networks | Enterprise networks |

## 📂 Project Structure

- router-on-a-stick/
- layer3-switch/

## 🧠 What I Learned

- VLAN segmentation
- Inter-VLAN routing
- Difference between L2 and L3 switching
