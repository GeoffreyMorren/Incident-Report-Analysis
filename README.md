<h1 align="center">
  Incident report analysis
</h1>

<h2 align="center">
  Summary
</h2>

<p align="center">
  Recently, the company was hit by a DDoS attack which compromised the network for 2 hours. The network services suddenly stopped responding due to an incoming flood of ICMP packets. As a result, normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. During the investigation, the cybersecurity team found that a malicious actor had been able to send a flood of ICMP pings into the company’s network through an unconfigured firewall.
</p>
<p align="center">
  Following the attack, the network security team implemented a new firewall rule to limit the rate of incoming ICMP packets, source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets, network monitoring software to detect abnormal traffic patterns and an IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics.
</p>

<h2 align="center">
  Identify
</h2>

<p align="center">
  The incident management team noticed the incoming flood of ICMP packets and responded by blocking incoming ICMP packets, stopping all non-critical network services offline. During the investigation, the cybersecurity team found that a malicious actor had been able to send a flood of ICMP pings into the company’s network through an unconfigured firewall.
</p>

<h2 align="center">
  Protect
</h2>

<p align="center">
  The network security team implemented a new firewall rule to limit the rate of incoming ICMP packets, source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets, network monitoring software to detect abnormal traffic patterns and an IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics.
</p>

<h2 align="center">
  Detect
</h2>

<p align="center">
  The network security team implemented network monitoring software to detect abnormal traffic patterns and an IDS/IPS system.
</p>

<h2 align="center">
  Respond
</h2>

<p align="center">
  The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline. The network monitoring software, along with the IDS/IPS system, will allow for future active monitoring and quickly be able to respond to abnormal traffic.
</p>

<h2 align="center">
  Recover
</h2>

<p align="center">
  After blocking incoming ICMP packets and stopping all non-critical network services, the incident management team started restoring critical network services. It is advised to create regular back ups of the system and store these offline for a faster recovery should a similar event occur in the future.
</p>
