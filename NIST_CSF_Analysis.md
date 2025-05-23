# NIST CSF-Based Analysis of DDoS Incident

## 1. 🧭 Identify

- **Assets Affected**: Network infrastructure, servers, firewalls
- **Business Impacted**: Web design, social media, and graphic design services disrupted
- **Security Gaps Found**: No rate-limiting on ICMP traffic, unconfigured firewall rules

---

## 2. 🛡️ Protect

- Implemented a new firewall rule to rate-limit incoming ICMP packets
- Source IP address verification enabled to detect spoofed traffic
- Staff trained on firewall configuration and DDoS response

---

## 3. 🔎 Detect

- Deployed network monitoring software to detect abnormal traffic spikes
- IDS/IPS systems configured to flag and filter suspicious ICMP packets
- Established SIEM logging to provide better visibility and alerting

---

## 4. 🚨 Respond

- Blocked incoming ICMP packets during the attack
- Took non-critical services offline to preserve critical operations
- Documented response actions and communicated with key stakeholders

---

## 5. 🛠️ Recover

- Restored critical systems after blocking attack vectors
- Validated all systems were operational post-attack
- Reviewed and revised firewall policies and recovery protocols
