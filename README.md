# Shivam Kumar
**Network Infrastructure Specialist & AI Systems Developer**

Designing resilient enterprise network topologies and building high-throughput, asynchronous AI & backend systems.

[LinkedIn](https://linkedin.com/in/your-linkedin-handle) · [LeetCode](https://leetcode.com/u/your-leetcode-handle) · [GitHub](https://github.com/Shivam-kumar-92) · [Email](mailto:your.email@example.com)

---

## Core Engineering Pillars

### Network Engineering & Security
- **Enterprise Topology & Routing:** Dual-router High Availability (HSRP v2), dynamic routing (BGP/OSPF), 802.1Q VLAN segmentation, Rapid-PVST+, and zero-trust ACLs.
- **NOC Monitoring & Fault Isolation:** Automated endpoint telemetry, SLA/MTTR tracking, packet-level Root Cause Analysis (DNS, TCP, TLS, ARP), and cyber threat mitigation (DAI, DHCP Snooping, SSH hardening, UFW/Fail2Ban).

### AI & Backend Systems
- **AI Pipelines & Data Engineering:** Multi-tier LLM extraction workflows, structured prompt engineering, entity resolution, and token/cost optimization.
- **Async Backend & Interfaces:** High-concurrency `asyncio` web scraping & orchestration, RESTful backends, relational data modeling, and voice/intent-driven web interfaces.

---

## Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **Networking & Security** | Cisco Packet Tracer, Cisco IOS, TCP/IP, BGP/OSPF, HSRP, VLANs, Wireshark (`tshark`), Linux Networking, AWS VPC, Terraform |
| **Languages & Frameworks** | Python, Java, JavaScript, Spring Boot, React, Bash |
| **AI & Data** | LLM APIs, Prompt Engineering, `asyncio`, Web Speech API, Prisma, SQL (PostgreSQL / SQLite) |

---

## Featured Architecture & Code

### Networking & Infrastructure
1. **[Automated NOC Health Monitor & Alerting Bot](https://github.com/Shivam-kumar-92/Automated-NOC-Health-Monitor-Alerting-Bot-Highest-Edge-)**
   Zero-dependency Python/Linux daemon performing concurrent ICMP + TCP port checks (`22/53/80/443`), SQLite SLA tracking, automated CSV log rotation, and real-time Discord/Slack/Telegram outage & recovery alerts.
2. **[Wireshark Packet Capture & Network Incident RCA Portfolio](https://github.com/Shivam-kumar-92/Wireshark-Packet-Capture-Network-Incident-RCA-Portfolio)**
   Four real `.pcap` enterprise failure investigations (DNS `NXDOMAIN`/`SERVFAIL`, TCP `SYN` firewall drop vs. `RST`, HTTP vs. TLS 1.2 handshake, ARP spoofing/Duplicate IP) with remediation runbooks and a Python forensic CLI validated by `tshark` in CI.
3. **[High-Availability Enterprise Network + Hardened Linux Bastion Lab (Cisco + AWS)](https://github.com/Shivam-kumar-92/High-Availability-Enterprise-Network-Linux-Bastion-Lab-Cisco-AWS-)**
   Dual-router Cisco HSRP v2 + OSPF Area 0 + split-scope DHCP campus lab paired with a Terraform-provisioned AWS private subnet, SG-to-SG Bastion host, UFW/Fail2Ban hardening, and automated SHA-256 cron backups.

### AI & Software Systems
4. **[Multi-Tier LLM Extraction & Entity Resolution Pipeline](https://github.com/Shivam-kumar-92/your-llm-pipeline-repo)** *(Placeholder — update link)*
   Asynchronous multi-stage document/web extraction engine combining deterministic parsers, schema-validated LLM prompts, and fuzzy/semantic entity deduplication into SQL via Prisma.
5. **[Async Web Intelligence & High-Concurrency Scraper](https://github.com/Shivam-kumar-92/your-async-scraper-repo)** *(Placeholder — update link)*
   `asyncio`-powered distributed scraper with rate-limiting, exponential backoff retries, structured JSON/SQL persistence, and automated anomaly alerts.
6. **[Voice & Intent-Driven AI Assistant Interface](https://github.com/Shivam-kumar-92/your-voice-ai-repo)** *(Placeholder — update link)*
   Full-stack React + Spring Boot / Python assistant leveraging the Web Speech API for low-latency voice capture, intent classification, and tool-augmented LLM responses.

---

## Currently Exploring
- Event-driven network automation combining **Python `asyncio` telemetry** with **LLM-assisted incident triage & automated RCA summarization**.
