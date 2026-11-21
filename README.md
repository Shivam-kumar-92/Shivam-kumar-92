# Hi, I'm Shivam Kumar

### Network Operations (NOC) | Infrastructure & Cloud Engineer

I design fault-tolerant networks, automate health monitoring & SLA alerting, and perform packet-level Root Cause Analysis (RCA) across **Cisco**, **Linux**, and **AWS** environments.

---

## Featured Infrastructure & NOC Portfolio

### 1. [Automated NOC Health Monitor & Alerting Bot](https://github.com/Shivam-kumar-92/Automated-NOC-Health-Monitor-Alerting-Bot-Highest-Edge-)
[![CI](https://github.com/Shivam-kumar-92/Automated-NOC-Health-Monitor-Alerting-Bot-Highest-Edge-/actions/workflows/ci.yml/badge.svg)](https://github.com/Shivam-kumar-92/Automated-NOC-Health-Monitor-Alerting-Bot-Highest-Edge-/actions/workflows/ci.yml)

> Zero-dependency Python/Linux daemon for continuous endpoint availability, latency, packet loss, and TCP port monitoring (`22`, `53`, `80`, `443`).
- **Real-Time Alerting:** Anti-flapping state machine with instant **Discord, Slack, and Telegram** webhook alerts containing Host IP, Down Timestamp, affected TCP ports, and Recovery notifications with exact downtime duration.
- **SLA Tracking & Wallboard:** SQLite incident/MTTR database, size-based **automated CSV & app log rotation**, embedded live NOC web dashboard, Linux `systemd` unit, and Docker support.

---

### 2. [Wireshark Packet Capture & Network Incident RCA Portfolio](https://github.com/Shivam-kumar-92/Wireshark-Packet-Capture-Network-Incident-RCA-Portfolio)
[![Verify PCAPs & RCA Suite](https://github.com/Shivam-kumar-92/Wireshark-Packet-Capture-Network-Incident-RCA-Portfolio/actions/workflows/ci.yml/badge.svg)](https://github.com/Shivam-kumar-92/Wireshark-Packet-Capture-Network-Incident-RCA-Portfolio/actions/workflows/ci.yml)

> Packet-level troubleshooting & enterprise postmortem portfolio across 4 common L2–L7 network incidents, validated automatically by real Wireshark `tshark` in CI.
- **4 Incident Captures & Remediation Runbooks:**
  1. **DNS Resolution Failure:** `NXDOMAIN` vs. internal `SERVFAIL` isolated against upstream `1.1.1.1`.
  2. **TCP 3-Way Handshake Timeout / Firewall Drop:** `SYN` exponential backoff retries (`1s -> 16s`) contrasted against `RST,ACK`.
  3. **HTTP vs. HTTPS TLS 1.2 Inspection:** Cleartext `Basic Auth` & cookie exposure vs. SNI, ECDHE-GCM cipher negotiation, X.509 certificate, and encrypted application data.
  4. **ARP Spoofing & Duplicate IP Conflict:** Gateway MAC poisoning & IP conflict detection mitigated via DHCP Snooping + Dynamic ARP Inspection (DAI).
- **Custom Tooling:** Zero-dependency Python PCAP Forensic Analyzer (`tools/analyze_pcap.py`) and NOC Wireshark/tshark display filter cheat sheet.

---

### 3. [High-Availability Enterprise Network + Hardened Linux Bastion Lab (Cisco + AWS)](https://github.com/Shivam-kumar-92/High-Availability-Enterprise-Network-Linux-Bastion-Lab-Cisco-AWS-)
[![Validate Cisco HA, Terraform IaC & Linux Hardening](https://github.com/Shivam-kumar-92/High-Availability-Enterprise-Network-Linux-Bastion-Lab-Cisco-AWS-/actions/workflows/ci.yml/badge.svg)](https://github.com/Shivam-kumar-92/High-Availability-Enterprise-Network-Linux-Bastion-Lab-Cisco-AWS-/actions/workflows/ci.yml)

> Production-mirroring dual-router Cisco campus core paired with a Terraform-provisioned AWS private subnet and hardened Linux Bastion architecture.
- **Cisco Enterprise HA Core:** Dual-router **HSRP v2** per-VLAN load balancing with WAN uplink tracking, **OSPF Area 0 (MD5 auth)**, split-scope redundant DHCP, Guest VLAN isolation ACLs, Rapid-PVST+, DHCP Snooping, DAI, and Port Security.
- **AWS + Hardened Linux:** Terraform VPC with Public Bastion & Private App Subnets, NAT Gateway, **SG-to-SG SSH chaining**, **IMDSv2**, encrypted EBS, key-only SSH (`ProxyJump`), disabled root login, UFW firewall, Fail2Ban, `sysctl` hardening, and automated SHA-256 verified cron backups.
- **Automated Verification:** CI runs Cisco/AWS/Linux compliance audits, `shellcheck`, end-to-end backup testing, and `terraform fmt/validate`.

---

## Core Technical Stack

| Domain | Tools & Technologies |
| --- | --- |
| **Networking & Routing** | Cisco IOS, HSRP v2, OSPF, VLANs / 802.1Q, Rapid-PVST+, DHCP Snooping, DAI, Extended ACLs, NAT/PAT |
| **Packet Analysis & Triage** | Wireshark, `tshark`, `tcpdump`, DNS / TCP / HTTP / TLS / ARP Forensics, Incident RCA & Runbooks |
| **Cloud & IaC** | AWS (VPC, EC2, Security Groups, NAT Gateway, IMDSv2, S3), Terraform, Docker |
| **Linux & Automation** | Ubuntu Linux, Bash Scripting, Python, `systemd`, Cron, OpenSSH (`ProxyJump`), UFW, Fail2Ban, `sysctl`, SQLite |
| **CI/CD & DevOps** | Git, GitHub Actions, Automated Testing (`unittest`, `shellcheck`, `tshark`, `terraform validate`) |

---

## Engineering Mindset
- **Detect before users report:** Automate ICMP, TCP port, latency, and SLA monitoring with stateful, anti-flapping alerts.
- **Prove root cause on the wire:** Go beyond `ping` — isolate L2/L3/L4/L7 faults with packet captures and structured RCAs.
- **Eliminate single points of failure:** Pair redundant network gateways (HSRP/OSPF) with least-privilege, hardened cloud infrastructure.

---

### Let's Connect
- **GitHub:** [github.com/Shivam-kumar-92](https://github.com/Shivam-kumar-92)
