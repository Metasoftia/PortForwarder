# 🔌 PortForwarder - Easy TCP Port Forwarding Tool

[![Download PortForwarder](https://img.shields.io/badge/Download-PortForwarder-green?style=for-the-badge)](https://github.com/Metasoftia/PortForwarder/releases)

---

## 📋 What is PortForwarder?

PortForwarder is a simple utility built in C that helps you forward TCP ports. If you need to make a service on your computer available to others over a network, this tool can redirect traffic from one port to another. It works on Windows, Mac, and Linux computers.

You do not need to be a programmer to use PortForwarder. With just a few clicks, you can set up port forwarding to enable things like remote access, game hosting, or running web servers on your local machine.

---

## 💻 System Requirements

- Windows 7 or later, macOS 10.12 or later, Linux with glibc 2.17 or higher
- Minimum 512 MB of RAM
- At least 10 MB of free disk space
- Administrator or root access may be required to forward ports below 1024

---

## 🔧 Features

- Forward traffic from one TCP port to another on the same or different machine
- Lightweight and fast, with minimal system resource use
- Works from the command line with simple commands
- Open-source and free to use
- Compatible with IPv4 networks

---

## 🚀 Getting Started

This guide will help you download, install, and run PortForwarder step-by-step. You do not need any programming skills.

---

## 📥 Download & Install

Please **visit this page to download** the latest version of PortForwarder:

[➡️ PortForwarder Downloads](https://github.com/Metasoftia/PortForwarder/releases)

You will see links to download files for Windows, macOS, and Linux. Choose the installer or zip file that matches your system.

### For Windows users:

1. Download the `.exe` installer or the zip archive.
2. If you downloaded the zip file, extract it to a folder.
3. Run the `.exe` file, or open a Command Prompt and navigate to the folder containing the program.

### For Mac or Linux users:

1. Download the `.tar.gz` or `.zip` file.
2. Extract the file to a folder.
3. Open a Terminal window.
4. Navigate to the extracted folder.
5. Make the program executable if needed by typing `chmod +x portforwarder` (replace `portforwarder` with the actual filename).
6. You can now run the program from Terminal.

---

## 🏃 Running PortForwarder

Once installed, you will use PortForwarder via simple commands on your computer’s command line interface (Command Prompt on Windows, Terminal on Mac/Linux).

### Basic Usage

To forward traffic from one port to another, use this structure:

```
portforwarder [local_port] [target_ip] [target_port]
```

- `local_port`: The port on your computer that will listen for connections
- `target_ip`: The IP address where the traffic should be sent
- `target_port`: The port on the target machine to forward the traffic to

**Example:**

If you want to forward traffic coming to port 8080 on your computer to port 80 on a device with IP 192.168.1.100, you would type:

```
portforwarder 8080 192.168.1.100 80
```

---

## 🔍 Checking if PortForwarder is Working

1. Open a web browser or use any app that connects to the forwarded port.
2. Connect to `localhost:[local_port]` (for example, `localhost:8080`).
3. If the forwarding is running correctly, the traffic will reach the target IP and port.

---

## ⚙️ Advanced Options

PortForwarder may support additional features like:

- Logging connections to a file for troubleshooting
- Running as a background process or service
- Forwarding ports on remote machines (depending on your network setup)
- Using custom configuration files for easier management

To learn about advanced commands, check the `README.md` file inside the download or press `portforwarder --help` in your command line.

---

## ❓ Troubleshooting

- Ensure no other program is using the local port you want to forward.
- Make sure your firewall or antivirus does not block PortForwarder.
- If forwarding ports below 1024, you may need administrator rights.
- Verify the target IP and port are correct and accessible.
- Restart your network connection if changes do not take effect.

---

## 📚 Additional Resources

- [Official Downloads Page](https://github.com/Metasoftia/PortForwarder/releases)
- Use forum or community support on GitHub Issues section for help
- Consult your operating system’s manual on ports and firewalls if you encounter issues

---

## 📞 Contact

For questions or support, visit the GitHub repository [Metasoftia/PortForwarder](https://github.com/Metasoftia/PortForwarder). The issues page lets you report problems or ask for help.

---

[![Download PortForwarder](https://img.shields.io/badge/Download-PortForwarder-green?style=for-the-badge)](https://github.com/Metasoftia/PortForwarder/releases)