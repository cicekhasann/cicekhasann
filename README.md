# Hasan Çiçek
### Systems & Backend Engineer | Network Infrastructure & Security

[linkedin/cicekhasan](https://linkedin.com/in/cicekhasan)

---

```bash
hasan@workstation:~$ cat /etc/motd
```

```yaml
host: workstation-01
os_kernel: "FreeBSD 14.x / Linux 6.x (Custom netns & PF runtime)"
engineer: "Hasan Çiçek"
current_role: "Systems & Backend Engineer @ ePati Cyber Security"
core_subsystems:
  - "Low-Level Network Architecture & IPsec Automation"[cite: 10]
  - "Distributed High-Availability Clustering Daemons"[cite: 10]
  - "High-Throughput Packet Logging & Memory Profiling"[cite: 10]
```

---

```bash
hasan@workstation:~$ dmesg --level=notice,crit | grep -E "HA|NET|MEM"
```

```diff
+ [    0.004120] HA-DAEMON: Active-Active heartbeat established. Target 99.99% uptime ok.[cite: 10]
+ [    0.012480] NET-CORE : 30,000+ netns veth pairs provisioned. Throughput ~2 Gbps stable.[cite: 10]
+ [    0.021040] MEM-TUNE : Production footprint optimized by ~30%, query sync +25% faster.[cite: 10]
+ [    0.034500] SEC-ENG  : StrongSwan VICI & Snort IDS/IPS daemons attached to IPC domain sockets.[cite: 10]
```

---

```bash
hasan@workstation:~$ ps aux --sort=-%cpu | head -n 6
```

```yaml
USER       PID   %CPU  %MEM  COMMAND
root       101    8.4   2.1  ha-cluster-daemon --subsecond-heartbeat[cite: 10]
root       102    6.2   3.4  strongswan-vici-netns-controller[cite: 10]
hasan      103    4.5   1.8  c-packet-filter-engine (PF/ipfw)[cite: 10]
hasan      104    3.8   2.2  node /opt/epati/services/orchestrator.js[cite: 10]
docker     105    2.9   4.1  dockerd --swarm-mode --production[cite: 10]
```

---

```bash
hasan@workstation:~$ cat /etc/network/interfaces.d/stack.conf
```

```yaml
# Languages & Runtimes:
LANGUAGES="C, C++, Node.js, TypeScript, POSIX Shell/Bash, Go"[cite: 5, 10]

# Network & Security Subsystems:
FIREWALL_VPN="Linux netns, FreeBSD PF, StrongSwan IPsec, Snort IDS/IPS, ZTNA"[cite: 10]

# Orchestration & Storage:
INFRASTRUCTURE="Docker Swarm, Kubernetes, PostgreSQL, Redis, GCP, Syslog-ng"[cite: 10]
```

---

```bash
hasan@workstation:~$ curl -s [https://api.github.com/users/cicekhasann/telemetry](https://api.github.com/users/cicekhasann/telemetry)
```

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=cicekhasann&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="150" alt="Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=cicekhasann&theme=tokyonight&hide_border=true" height="150" alt="Streak" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=cicekhasann&theme=tokyonight&hide_border=true&layout=compact" height="135" alt="Langs" />
</p>

---

```bash
hasan@workstation:~$ uptime
```
```text
System load: optimal. Telemetry counter:
```
