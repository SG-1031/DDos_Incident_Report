# Incident Report: DDoS Attack

## Summary

A Distributed Denial of Service (DDoS) attack using a flood of ICMP packets targeted our multimedia company's internal network, rendering it unresponsive for two hours. The attack exploited a misconfigured firewall, allowing traffic from external malicious sources. The incident was mitigated by blocking ICMP packets, taking non-critical services offline, and restoring essential services.

---

## Incident Details

- **Type of attack**: Distributed Denial of Service (DDoS) using ICMP flood
- **Cause**: Firewall misconfiguration allowed external ICMP traffic
- **Duration**: 2 hours
- **Impact**: Full internal network service outage
- **Response**: Blocked ICMP, restored critical services, implemented firewall fixes
- **Root Cause**: Lack of rate-limiting and source verification in firewall settings

---

## Estimated Impact

- Loss of network connectivity internally
- Disruption to client-facing services
- Potential reputational damage
