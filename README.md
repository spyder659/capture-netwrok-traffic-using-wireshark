# capture-netwrok-traffic-using-wireshark

# Task 5: Capture and Analyze Network Traffic Using Wireshark

## ->Objective
To capture live network traffic using Wireshark, identify commonly used protocols, and summarize findings for protocol awareness and troubleshooting practice.

---

## -> Tools Used
- **Wireshark** (Free network protocol analyzer)

---

## -> Steps Performed

### 1. Installed Wireshark
I have already Installed the latest version of Wireshark from the official website:  
🔗 [https://www.wireshark.org/download.html](https://www.wireshark.org/download.html)

### 2. Started Packet Capture
- I had chosed the Ethernet netwrok interface.
- Clicked on the **Shark Fin icon** to start capturing.

### 3. Generated Network Traffic
- Opened a browser and visited:
  - `https://example.com`
  - Ran `ping google.com` in the terminal to simulate additional traffic.

### 4. Stopped Capture
- Let the capture run for around 60 seconds.
- Clicked the red **Stop icon** to end the session.

### 5. Filtered by Protocol
I used Wireshark's filter bar to inspect specific protocols:
- `http`
- `dns`
- `tcp`

### 6. Identified Protocols
Observed traffic related to:
- **HTTP**: Web browsing data
- **DNS**: Domain name resolution
- **TCP**: Underlying connection protocol[task_5cap.txt](https://github.com/user-attachments/files/20980355/task_5cap.txt)


### 7. Exported Capture
I had saved the packet capture file as:
[task5cap.txt](https://github.com/user-attachments/files/20980470/task5cap.txt)
