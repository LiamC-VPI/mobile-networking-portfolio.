# mobile-networking-portfolio.
Practical network laboratories, protocol analysis, and security reconnaissance documentation compiled in preparation for SCQF Level 6 Networking studies.

# SCQF Level 6 Networking Mobile Lab Portfolio

A professional laboratory repository documenting network infrastructure, transport layer protocols, and tactical diagnostic verification labs conducted entirely within a mobile architecture.

## 🛠️ Lab 1: Text-Based Socket Protocol Verification (FICS)
- **Objective:** Intercept and evaluate a live, bidirectional application layer data stream.
- **Protocol / Port:** Telnet / TCP Port 5000
- **Target Host:** `freechess.org`
- **Core Mechanics:** Established an active socket connection to parse real-time asynchronous stream payloads. Evaluated game state changes, packet structural framing, and low-latency text-art presentation layers directly within a terminal console.

## 🔍 Lab 2: Network Infrastructure Reconnaissance & Service Auditing
- **Objective:** Identify operational local area network nodes, service configurations, and software versions.
- **Tooling:** Nmap 7.99
- **Target Gateway:** `192.168.1.254` (Default Gateway)
- **Discovered Parameters:**
  - **Port 5000/TCP:** Open
  - **Service Daemon:** `MiniUPnP 2.3.7` (UPnP 1.1 protocol handler)
  - **Host Operating System:** `OpenWrt` (Linux Kernel Version `5.15.167`)
- **Core Mechanics:** Conducted active probing and banner grabbing using specific advanced scanning criteria (`-sV`). Captured raw HTTP response headers and service fingerprints to map the underlying network system architecture.

---
*Maintained and documented directly from an Android Linux terminal environment (Termux).*
EOF
Initial commit: Populated FICS stream and Nmap reconnaissance documentation"
