# Scalable SIEM Lab with Elastic Stack: Enhancing Security Visibility

**Duration**: Aug 2024 - Sep 2024

## Project Overview

This project focuses on building a **Scalable Security Information and Event Management (SIEM) system** using the **Elastic Stack**. It demonstrates skills in **log management**, **data ingestion**, **threat detection**, and **real-time monitoring**. By leveraging **Kibana dashboards**, I was able to visualize security events, improving incident response and security operations.

This hands-on project showcases my expertise in **cybersecurity** and the effective use of operational security tools like **Elastic Stack** to enhance visibility and response times in a **Security Operations Center (SOC)**.

### Key Components of the Project:
1. **Log Management & Data Ingestion**
   - Configured log ingestion pipelines from various sources (e.g., system logs, firewall logs) using **Beats** and **Logstash**.
   - Implemented scalable data storage solutions using **Elasticsearch**.

2. **Threat Detection & Analysis**
   - Created custom rules to detect anomalous behavior using **Elasticsearch Query Language (EQL)**.
   - Used machine learning features of Elastic to identify advanced persistent threats (APTs).

3. **Incident Response & Monitoring**
   - Developed and optimized **Kibana** dashboards to provide real-time insights into security events.
   - Monitored security events continuously and created automated alerts for incident response.

4. **Security Operations Center (SOC) Monitoring**
   - Used the SIEM system for **SOC monitoring**, visualizing key metrics such as user login patterns, suspicious IP addresses, and failed login attempts.
   - Enhanced incident response through automation and custom alerting mechanisms.

## Project Details

### 1. Log Management & Data Ingestion
- Used **Filebeat** and **Winlogbeat** for ingesting system and application logs.
- Data was processed and filtered through **Logstash** to ensure relevant data was indexed into **Elasticsearch**.
- Configured pipelines to scale and handle large volumes of log data.

### 2. Threat Detection & Analysis
- Custom **Kibana dashboards** were built to visualize security events.
- Set up **detection rules** for threats like brute force attacks, privilege escalation, and insider threats.
- Used **Elasticsearch's machine learning** capabilities to detect anomalous patterns in logs.

### 3. Incident Response & Monitoring
- Developed automated **alerts** for critical events such as failed logins and suspicious IP addresses.
- Monitored incidents in real time using **Kibana's monitoring tools**.
- Integrated Elastic’s **SIEM detection engine** to enable rapid response.

### 4. Security Operations Center (SOC) Monitoring
- Deployed the solution in a SOC environment to monitor security events in real time.
- Utilized **Kibana's visualization tools** to create actionable insights for security analysts.
- Improved SOC efficiency by reducing response times and minimizing false positives.

## Tools and Technologies Used:
- **Elastic Stack (Elasticsearch, Kibana, Logstash, Beats)**
- **Kibana Dashboards**
- **Linux & Windows Servers**
- **Threat Intelligence & SIEM Detection**

## Repository Structure
```bash
scalable-siem-lab-elastic-stack/
│
├── README.md                     # Project Overview
├── log-management/                # Configurations for log ingestion
├── threat-detection/              # Custom rules and queries for threat detection
├── incident-response/             # Kibana dashboards and alerts
└── soc-monitoring/                # SOC monitoring configurations and scripts
