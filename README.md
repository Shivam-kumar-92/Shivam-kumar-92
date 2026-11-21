<div align="center">
  <img src="assets/banner.svg" alt="Shivam Kumar - NOC, Infrastructure & Cloud SRE Banner" width="100%" />
</div>

<p align="center">
  <a href="https://github.com/Shivam-kumar-92">
    <img src="https://img.shields.io/badge/GitHub-Shivam--kumar--92-0F172A?style=for-the-badge&logo=github&logoColor=38BDF8" alt="GitHub" />
  </a>
  <img src="https://img.shields.io/badge/Focus-NOC%20%7C%20Network%20%7C%20Cloud%20SRE-052E16?style=for-the-badge&logo=cloudflare&logoColor=22C55E" alt="Focus" />
  <img src="https://img.shields.io/badge/CI%20Verified-All%203%20Core%20Labs%20Passing-1E1B4B?style=for-the-badge&logo=githubactions&logoColor=818CF8" alt="CI Verified" />
</p>

---

### `whoami` — Engineering Profile

```bash
$ cat /etc/noc/engineer-profile.yml
name:      Shivam Kumar
role:      Network Operations (NOC) | Infrastructure & Cloud Engineer
strengths:
  - Automated network health monitoring, SLA tracking & real-time webhook alerting
  - Packet-level troubleshooting & Root Cause Analysis (DNS, TCP, TLS, ARP)
  - Fault-tolerant Cisco enterprise routing (HSRP v2, OSPF, VLANs, ACLs, DAI)
  - Hardened Linux administration & AWS VPC private-subnet Bastion IaC (Terraform)
```

---

## Featured Production-Grade Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>1. <a href="https://github.com/Shivam-kumar-92/Automated-NOC-Health-Monitor-Alerting-Bot-Highest-Edge-">Automated NOC Health Monitor &amp; Alerting Bot</a></h3>
      <p>
        <a href="https://github.com/Shivam-kumar-92/Automated-NOC-Health-Monitor-Alerting-Bot-Highest-Edge-/actions/workflows/ci.yml">
          <img src="https://github.com/Shivam-kumar-92/Automated-NOC-Health-Monitor-Alerting-Bot-Highest-Edge-/actions/workflows/ci.yml/badge.svg" alt="Project 1 CI" />
        </a>
        <img src="https://img.shields.io/badge/Python-Zero%20Deps-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/SQLite-SLA%20Tracking-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
      </p>
      <p>Lightweight Python/Linux monitoring daemon tracking endpoint availability, ICMP latency/packet loss, and TCP ports (<code>22</code>, <code>53</code>, <code>80</code>, <code>443</code>).</p>
      <ul>
        <li><strong>Stateful Alerting:</strong> Anti-flapping hysteresis + instant Discord, Slack &amp; Telegram alerts with Host IP, Down Timestamp &amp; Recovery duration.</li>
        <li><strong>SLA &amp; Ops Ready:</strong> SQLite MTTR tracking, automated CSV/app log rotation, live NOC web dashboard, <code>systemd</code> unit &amp; Docker support.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>2. <a href="https://github.com/Shivam-kumar-92/Wireshark-Packet-Capture-Network-Incident-RCA-Portfolio">Wireshark PCAP &amp; Network Incident RCA Portfolio</a></h3>
      <p>
        <a href="https://github.com/Shivam-kumar-92/Wireshark-Packet-Capture-Network-Incident-RCA-Portfolio/actions/workflows/ci.yml">
          <img src="https://github.com/Shivam-kumar-92/Wireshark-Packet-Capture-Network-Incident-RCA-Portfolio/actions/workflows/ci.yml/badge.svg" alt="Project 2 CI" />
        </a>
        <img src="https://img.shields.io/badge/Wireshark-tshark%20Validated-1679A7?style=flat-square&logo=wireshark&logoColor=white" alt="Wireshark" />
        <img src="https://img.shields.io/badge/OSI-L2%20to%20L7-22C55E?style=flat-square" alt="OSI" />
      </p>
      <p>Packet-level troubleshooting &amp; postmortem portfolio across 4 enterprise network incidents — every <code>.pcap</code> verified with zero malformed frames by real <code>tshark</code> in CI.</p>
      <ul>
        <li><strong>4 Deep-Dive RCAs:</strong> DNS <code>NXDOMAIN</code>/<code>SERVFAIL</code> isolation, TCP <code>SYN</code> firewall drop vs. <code>RST</code>, HTTP cleartext vs. TLS 1.2 cert/cipher, and ARP spoofing + Duplicate IP.</li>
        <li><strong>Custom Tooling:</strong> Zero-dependency Python PCAP Forensic Analyzer &amp; NOC Wireshark filter cheat sheet.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>3. <a href="https://github.com/Shivam-kumar-92/High-Availability-Enterprise-Network-Linux-Bastion-Lab-Cisco-AWS-">High-Availability Enterprise Network + Hardened Linux Bastion Lab (Cisco + AWS)</a></h3>
      <p>
        <a href="https://github.com/Shivam-kumar-92/High-Availability-Enterprise-Network-Linux-Bastion-Lab-Cisco-AWS-/actions/workflows/ci.yml">
          <img src="https://github.com/Shivam-kumar-92/High-Availability-Enterprise-Network-Linux-Bastion-Lab-Cisco-AWS-/actions/workflows/ci.yml/badge.svg" alt="Project 3 CI" />
        </a>
        <img src="https://img.shields.io/badge/Cisco-HSRP%20v2%20%7C%20OSPF-049FD9?style=flat-square&logo=cisco&logoColor=white" alt="Cisco" />
        <img src="https://img.shields.io/badge/Terraform-AWS%20VPC-7B42BC?style=flat-square&logo=terraform&logoColor=white" alt="Terraform" />
        <img src="https://img.shields.io/badge/Linux-Hardened%20Bastion-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
      </p>
      <p>Production-mirroring dual-router Cisco campus core paired with a Terraform-provisioned AWS VPC, private subnet, and hardened Ubuntu Linux Bastion architecture.</p>
      <ul>
        <li><strong>Cisco HA Core:</strong> Per-VLAN load-balanced <strong>HSRP v2</strong> with WAN uplink tracking, <strong>OSPF Area 0 (MD5 auth)</strong>, split-scope redundant DHCP, Guest isolation ACLs, Rapid-PVST+, DHCP Snooping, DAI &amp; Port Security.</li>
        <li><strong>AWS &amp; Linux Security:</strong> SG-to-SG SSH chaining, OpenSSH <code>ProxyJump</code>, key-only auth, disabled root login, UFW default-deny, Fail2Ban, <code>sysctl</code> hardening, IMDSv2, encrypted EBS, and SHA-256 verified daily cron backups — validated via <code>shellcheck</code> &amp; <code>terraform validate</code> in CI.</li>
      </ul>
    </td>
  </tr>
</table>

---

## Tech Stack & Operations Toolkit

<p align="center">
  <strong>Networking &amp; Packet Forensics</strong><br />
  <img src="https://img.shields.io/badge/Cisco%20IOS-049FD9?style=for-the-badge&logo=cisco&logoColor=white" alt="Cisco IOS" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" alt="Wireshark" />
  <img src="https://img.shields.io/badge/HSRP%20%7C%20OSPF%20%7C%20VLANs-0F172A?style=for-the-badge&logoColor=38BDF8" alt="HSRP OSPF VLANs" />
  <img src="https://img.shields.io/badge/TCP%2FIP%20%7C%20DNS%20%7C%20TLS-0F172A?style=for-the-badge&logoColor=22C55E" alt="TCP/IP DNS TLS" />
</p>

<p align="center">
  <strong>Cloud, Infrastructure-as-Code &amp; Containers</strong><br />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900" alt="AWS" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

<p align="center">
  <strong>Systems, Scripting &amp; Security</strong><br />
  <img src="https://img.shields.io/badge/Linux%20(Ubuntu)-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu Linux" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

---

## Engineering Principles

| Principle | How I Apply It |
| :--- | :--- |
| **Proactive Detection** | Build automated ICMP, TCP port, latency & SLA monitors with stateful anti-flapping alerts so incidents are caught before user tickets arrive. |
| **Packet-Level Truth** | Go beyond `ping` — diagnose DNS, TCP handshakes, TLS negotiation, and L2 ARP anomalies directly on the wire with documented remediation runbooks. |
| **Defense-in-Depth & HA** | Eliminate single points of failure (HSRP/OSPF/split-scope DHCP) and lock down cloud Linux workloads with private subnets, Bastion `ProxyJump`, UFW, and automated backups. |

---

<div align="center">
  <img src="assets/footer.svg" alt="Open to NOC, Network & Cloud SRE Roles" width="100%" />
</div>
