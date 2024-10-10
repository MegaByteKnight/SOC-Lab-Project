# SOC Lab Project

## Objective
The SOC (Security Operations Center) Lab project focuses on creating a controlled environment to simulate real-world cyber attack scenarios and practice incident response techniques. The main objective was to deploy a SIEM system to capture, analyze, and respond to network events, honing both defensive and investigative skills in a lab setting.

## Skills Learned
- Hands-on experience with setting up and managing a SIEM (Security Information and Event Management) system.
- Practical application of network security concepts such as detecting and responding to intrusion attempts.
- Enhanced ability to analyze network traffic using tools like Wireshark, interpreting logs to identify potential security breaches.
- Familiarity with MITRE ATT&CK framework and identifying attacker Tactics, Techniques, and Procedures (TTPs).
- Proficiency in configuring firewall rules and monitoring suspicious activities.

## Tools Used
- **pfSense Firewall**: Configured for monitoring and managing network traffic.
- **Splunk/Elastic SIEM**: Ingested logs from multiple sources and set up alerts to detect suspicious activities.
- **Wireshark**: Analyzed captured network traffic for signs of potential threats.
- **Azure Virtual Machines**: Deployed virtual infrastructure to simulate attacks and defense mechanisms.
- **Telemetry Generators**: Created test traffic and network events to mimic attack scenarios.

## Steps

### 1. Network Setup
Deployed a pfSense firewall and configured it to monitor network traffic between the virtualized environment and the external network.

![Network Setup Screenshot](link_to_image)

*Explanation*: This screenshot illustrates the network architecture where pfSense acts as the core firewall managing inbound and outbound traffic for the virtualized SOC lab.

---

### 2. SIEM Configuration
Installed and configured a SIEM system (Splunk/Elastic) to collect logs from Azure virtual machines, pfSense, and other endpoints.

![SIEM Setup Screenshot](link_to_image)

*Explanation*: Here, you can see the log sources feeding into the SIEM platform, including authentication attempts, firewall rules, and network traffic logs.

---

### 3. Simulating Attacks and Analyzing Logs
Simulated attacks such as brute force login attempts, network scans, and suspicious RDP connections. Captured the network traffic and generated alerts in the SIEM system for analysis.

![Log Analysis Screenshot](link_to_image)

*Explanation*: This shows the detailed log analysis within the SIEM system, where alerts for multiple failed login attempts triggered a firewall block rule.

---

### 4. Incident Response
Responded to triggered alerts by analyzing the logs, identifying malicious traffic, and creating firewall rules to block malicious IPs.

![Incident Response Screenshot](link_to_image)

*Explanation*: This demonstrates the incident response actions taken, such as identifying a suspicious IP performing a brute force attack and blocking it using pfSense.

---

This project helped develop critical incident response skills and demonstrated the use of various tools to detect and mitigate cyber threats.
