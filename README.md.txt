# 🛡️ Cyber Security Internship - Task 5

## 📌 Task Title: Wireshark Traffic Analysis

### 🎯 Objective:
Capture live network traffic using Wireshark and analyze key protocols to understand basic packet behavior and communication flow.

---

## 🧰 Tools Used:
- **Wireshark** (Version: 4.4.7, Windows x64)
- **Interface Used:** Wi-Fi

---

## 📦 Files Included:
- `tcp.pcapng` – TCP traffic capture
- `dns.pcapng` – DNS traffic capture
- `http.pcapng` – HTTP traffic capture
- `README.md` – Report and analysis summary

---

## 🔄 Steps Followed:
1. Installed Wireshark.
2. Captured traffic on the active network interface (Wi-Fi).
3. Generated traffic by browsing websites and using ping.
4. Stopped the capture after 1 minute.
5. Filtered captured packets using protocol filters (TCP, DNS, HTTP).
6. Identified and analyzed 3 different network protocols.
7. Saved the captures as `.pcapng` files.
8. Documented the findings below.

---

## 📡 Protocols Captured & Sample Analysis:

### 1. **HTTP**
- **Source IP:** `2401:::::::****`
- **Destination IP:** `2603:::::::****`
- **Method:** `POST`
- **Host:** `example.com`

### 2. **DNS**
- **Source IP:** `192...**`
- **Destination IP:** `192...**`
- **Query Name:** `chatgpt.com`

### 3. **TCP**
- **Source IP:** `2606:::::::****`
- **Destination IP:** `2401:::::::****`
- **TCP Flags:** `ACK`

---

## 🔐 Key Concepts Observed:
- Usage of `POST` in HTTP for data transmission
- DNS resolving domains like `chatgpt.com`
- TCP handshakes and acknowledgment flags (`ACK`)

---

