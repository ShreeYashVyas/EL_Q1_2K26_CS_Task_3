# EL_Q1_2K26_CS_Task_3
Elevate Labs task 3 repo

## 📌 Objective
Capture live network packets using Wireshark and analyze them to identify at least three different network protocols and their functionalities.

---

## 🛠 Tools Used
- **Wireshark** (Free packet analyzer for network traffic)

---

## 🧪 Steps Performed

1. **Installed Wireshark** on my system.
2. **Started a capture** on the active network interface (Wi-Fi).
3. **Generated network traffic** by browsing websites and pinging `google.com`.
4. Captured data for about **60 seconds** and then **stopped the capture**.
5. Applied filters to isolate different protocols like:
   - `http`
   - `dns`
   - `tcp`
6. Identified **at least three different protocols** in the capture:
   - **HTTP** – for web traffic.
   - **DNS** – for domain name resolution.
   - **TCP** – for reliable data transmission.
7. Exported the session as a `.pcap` file for documentation and submission.

--

## 📁 Deliverables

- ✅ `capture_task5.pcap` – exported Wireshark packet capture.
- ✅ `README.md` – this report.

---

## 📚 Key Concepts Practiced

- Packet capture and live analysis
- Protocol filtering in Wireshark
- Understanding TCP/IP stack and application-layer protocols
