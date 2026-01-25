# Network Cabling Lab

## 📌 Objectives
- Learn the fundamentals of Ethernet cabling used in computer networks.
- Identify end devices (Category A) and networking devices (Category B) based on TX/RX pins.
- Understand the principles of network cable termination and connectivity.
- Develop practical skills in testing and troubleshooting Ethernet cables for reliable performance.

---

## 🛠 Components Required
- Twisted Pair Cable (Cat 5e or Cat 6)
- RJ45 connectors
- Crimping tool (clamper)
- Network Cable Tester

---

## 📖 Theory
Ethernet is the backbone of most Local Area Networks (LANs). It uses **twisted-pair cables (Cat5/Cat6)** terminated with **RJ-45 connectors**. Each cable has 8 copper wires grouped into 4 twisted pairs, arranged according to **TIA/EIA-568A** or **TIA/EIA-568B** standards.

### Device Categories
- **Category A – End Devices** (PCs, laptops, printers):  
  - TX → Pins 1 & 2  
  - RX → Pins 3 & 6
- **Category B – Networking Devices** (Switches, hubs):  
  - TX → Pins 3 & 6  
  - RX → Pins 1 & 2

---

## 🔌 Connection Types

### 1. Straight-Through Cable
- Used to connect **different categories** (PC → Switch/Router).
- Both ends follow the **same wiring standard** (T568A–T568A or T568B–T568B).
- Ensures TX pins on end devices align with RX pins on networking devices.

**T568A Pinout Example:**
1. White-Orange  
2. Orange  
3. White-Green  
4. Blue  
5. White-Blue  
6. Green  
7. White-Brown  
8. Brown  

---

### 2. Crossover Cable
- Used to connect **similar devices** (PC → PC, Switch → Switch).
- One end uses **T568A**, the other uses **T568B**.
- TX and RX pins are swapped for direct communication.

**Crossover Pinout Example:**
- Side One (T568A): White-Orange, Orange, White-Green, Blue, White-Blue, Green, White-Brown, Brown  
- Side Two (T568B): White-Green, Green, White-Orange, Blue, White-Blue, Orange, White-Brown, Brown  

---

## 📊 Straight-Through vs Crossover Comparison

| Feature              | Straight-Through Cable                     | Crossover Cable                  |
|----------------------|---------------------------------------------|----------------------------------|
| **Wiring Standard**  | Both ends same (T568A–T568A / T568B–T568B) | Different ends (T568A–T568B)     |
| **Device Type**      | Different devices (PC → Switch/Router)     | Similar devices (PC → PC, Switch → Switch) |
| **Signal Direction** | Transmit/Receive straight                  | Transmit/Receive crossed         |
| **Common Use**       | Daily LAN connections                      | Peer-to-peer or testing setups   |

---

## 🔍 Observation
- Using a **Network LAN Tester**, both straight-through and crossover cables were tested.  
- Proper connectivity was indicated by **blinking LEDs** corresponding to pin numbers.

---

## 💬 Discussion
- Straight-through cabling is used for **different categories** of devices.  
- Crossover cabling is used for **same category** devices.  
- Initial mistakes in wiring direction were corrected with guidance, reinforcing the importance of following standards.

---

## ✅ Conclusion
The lab provided **hands-on experience** in preparing and testing Ethernet cables.  
Key learnings:
- Importance of wiring standards (T568A/T568B).  
- Correct cable type selection based on device categories.  
- Practical troubleshooting using a LAN tester.  

By completing this lab, we gained both **theoretical knowledge** and **practical skills** essential for reliable network cabling.