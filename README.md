# 🖥️ Simple TCP Chat Application with UTF-8 Encryption

## 📌 Description
This project is a **command-line chat application** using **TCP sockets**. It enables real-time messaging between a client and a server over a network. It supports **UTF-8 encrypted communication** and includes hostname identification for a better chat experience.

## ✨ Features
✅ Simple and lightweight TCP-based chat system  
✅ Supports **remote messaging** over a network  
✅ Displays **client hostname** for better tracking  
✅ Uses **UTF-8 encoding** for message transfer  
✅ **Multi-threaded server** for handling multiple clients  
✅ Color-coded output for better readability 🎨  

## 📦 Requirements
- Python 3.x
- `socket`, `threading`, `argparse` (Built-in Python modules)
- `colorama` and `pyfiglet` (Install using `pip` if not available)

## 🚀 Installation & Usage

### **1️⃣ Start the Server**
Run the following command on the machine acting as the **server**:
```bash
python server.py <host_ip> <port>
```
Example:
```bash
python server.py 127.0.0.1 8080
```
🔹 Replace `<host_ip>` with your **local or public IP address**.  
🔹 Replace `<port>` with an **available port** (e.g., `8080`).  

### **2️⃣ Start the Client**
Run the following command on another machine (or the same device) acting as the **client**:
```bash
python client.py <server_ip> <port>
```
Example:
```bash
python client.py 127.0.0.1 8080
```
🔹 `<server_ip>` should match the **server's IP**.  
🔹 `<port>` should match the **server’s listening port**.  

### **3️⃣ Sending & Receiving Messages**
✅ Type a message and press **Enter** to send it.  
✅ Messages from the other side will appear in the terminal.  
✅ To **exit**, type:
```bash
exit
```

## 🛠️ Troubleshooting
- If running both **server & client** on the **same device**, use `127.0.0.1` (localhost) as the IP.
- To allow **external devices** to connect, use your actual network IP (`ipconfig` on Windows, `ifconfig` on Linux/macOS).
- Ensure the **port is open** in your firewall if running over a network.

## ⚠️ Disclaimer
This project is for **educational and ethical use only**. Unauthorized use of this script on systems without permission is illegal.

---
🔹 **Author:** [ARUVASAGA CHITHAN](https://github.com/AruvasagaChithan)  
📌 **GitHub:** [AruvasagaChithan](https://github.com/aruvasaga-chithan)

