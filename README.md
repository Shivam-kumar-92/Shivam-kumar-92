# Shivam Kumar
**Network Infrastructure Specialist & AI Systems Developer**

Designing resilient enterprise network topologies and building high-throughput, asynchronous AI & backend systems.

[LinkedIn](https://www.linkedin.com/in/shivam-kumar-81b067305/) · [LeetCode](https://leetcode.com/u/shivam_kumar_93_/) · [GitHub](https://github.com/Shivam-kumar-92) · [Email](mailto:shivamkumarofficialit2005@gmail.com)

---

## Core Engineering Pillars

### Network Engineering & Security
- **Enterprise Topology & Routing:** Dual-router High Availability (HSRP v2), dynamic routing (BGP/OSPF), 802.1Q VLAN segmentation, Rapid-PVST+, and zero-trust ACLs.
- **NOC Monitoring & Fault Isolation:** Automated endpoint telemetry, SLA/MTTR tracking, packet-level Root Cause Analysis (DNS, TCP, TLS, ARP), and cyber threat mitigation (DAI, DHCP Snooping, SSH hardening, UFW/Fail2Ban).

### AI & Backend Systems
- **AI Pipelines & Data Engineering:** Multi-tier LLM extraction & RAG workflows, structured prompt engineering, entity resolution, and token/cost optimization.
- **Async Backend & Interfaces:** High-concurrency `asyncio` web scraping & orchestration, full-stack TypeScript/React/Spring Boot backends, Prisma/SQL modeling, and voice/multimodal AI interfaces.

---

## Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **Networking & Security** | Cisco Packet Tracer, Cisco IOS, TCP/IP, BGP/OSPF, HSRP, VLANs, Wireshark (`tshark`), Linux Networking, AWS VPC, Terraform |
| **Languages & Frameworks** | Python, Java, JavaScript, TypeScript, Spring Boot, React, Next.js, Bash |
| **AI & Data** | LLM APIs (Gemini, OpenAI, Claude), Semantic RAG, Prompt Engineering, `asyncio`, Web Speech API, Prisma, SQL (PostgreSQL / SQLite) |

---

## Featured Architecture & Code

### Networking & Infrastructure
1. **[Automated NOC Health Monitor & Alerting Bot](https://github.com/Shivam-kumar-92/Automated-NOC-Health-Monitor-Alerting-Bot-Highest-Edge-)**
   Zero-dependency Python/Linux daemon performing concurrent ICMP + TCP port checks (`22/53/80/443`), SQLite SLA tracking, automated CSV log rotation, and real-time Discord/Slack/Telegram outage & recovery alerts.
2. **[Wireshark Packet Capture & Network Incident RCA Portfolio](https://github.com/Shivam-kumar-92/Wireshark-Packet-Capture-Network-Incident-RCA-Portfolio)**
   Four real `.pcap` enterprise failure investigations (DNS `NXDOMAIN`/`SERVFAIL`, TCP `SYN` firewall drop vs. `RST`, HTTP vs. TLS 1.2 handshake, ARP spoofing/Duplicate IP) with remediation runbooks and a Python forensic CLI validated by `tshark` in CI.
3. **[High-Availability Enterprise Network + Hardened Linux Bastion Lab (Cisco + AWS)](https://github.com/Shivam-kumar-92/High-Availability-Enterprise-Network-Linux-Bastion-Lab-Cisco-AWS-)**
   Dual-router Cisco HSRP v2 + OSPF Area 0 + split-scope DHCP campus lab paired with a Terraform-provisioned AWS private subnet, SG-to-SG Bastion host, UFW/Fail2Ban hardening, and automated SHA-256 cron backups.
4. **[Async Subnet Health & Port Latency Monitor](https://github.com/Shivam-kumar-92/async-subnet-monitor)**
   Bounded-concurrency Python `asyncio` CIDR subnet scanner that probes TCP port handshake latencies (`22/53/80/443`) and exports structured JSON telemetry reports for NOC/SRE automation pipelines.

### AI & Software Systems
5. **[Yuktivya AI — Market Intelligence & AI Data Analyst Platform](https://github.com/Shivam-kumar-92/AI-analytics-)**
   TypeScript AI data analytics & market intelligence platform combining structured LLM reasoning pipelines with interactive data synthesis.
6. **[Nova Support AI — Multi-Engine RAG Customer Support Platform](https://github.com/Shivam-kumar-92/AI_AMZ)**
   Full-stack AI support platform featuring multi-engine reasoning across Gemini, OpenAI, Anthropic Claude, and built-in offline semantic RAG with knowledge-base retrieval.
7. **[AURA AI — Multimodal Voice & Vision Companion App](https://github.com/Shivam-kumar-92/Aura-AI-App)**
   Multimodal voice, vision, and collaborative AI companion featuring an audio-reactive interface and low-latency voice/intent-driven workflows.

---

## Currently Exploring
- Event-driven network automation combining **Python `asyncio` telemetry** with **LLM-assisted incident triage & automated RCA summarization**.
