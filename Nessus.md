# Tenable Vulnerability Management and Analysis

### Overview
Completed a project associated with **Tenable University** (July 2024) focused on deploying Nessus, performing vulnerability and compliance scans, and analyzing risks. The project involved configuring access controls, tagging assets, and utilizing dashboards to track security metrics. Produced detailed reports on security vulnerabilities and risk mitigation strategies to ensure compliance with industry standards.

## Table of Contents
1. [Project Description](#project-description)
2. [Skills & Technologies Used](#skills--technologies-used)
3. [Project Walk-through](#project-walk-through)
4. [Reports and Screenshots](#reports-and-screenshots)
5. [How to Run the Project](#how-to-run-the-project)
6. [License](#license)

## Project Description
This project involved the following key tasks:
- **Nessus Deployment**: Deployed and configured Nessus for scanning various assets across the network.
- **Vulnerability Scanning**: Performed both vulnerability and compliance scans to identify potential security weaknesses.
- **Access Controls**: Configured access controls to ensure proper permissions across the network.
- **Asset Tagging**: Tagged critical assets for targeted scanning and enhanced monitoring.
- **Dashboards**: Leveraged Tenable's dashboards to track key security metrics and vulnerabilities.
- **Reporting**: Generated detailed reports on vulnerabilities, including remediation recommendations to ensure compliance with industry standards.

## Skills & Technologies Used
- **Tenable Nessus**: Vulnerability scanner used to identify vulnerabilities and compliance issues.
- **Vulnerability Management**: Scanning, prioritizing, and reporting vulnerabilities based on risk.
- **Compliance Standards**: Ensured compliance with security standards such as CIS benchmarks, HIPAA, and ISO 27001.
- **Risk Mitigation**: Analyzed the risks and created action plans to reduce vulnerabilities.
- **Dashboards & Reports**: Used visual metrics and reporting features for tracking vulnerabilities.

## Project Walk-through

1. **Deploy Nessus**: 
   - Download and install Nessus on a server.
   - Configure network settings to scan internal and external assets.

2. **Perform Vulnerability and Compliance Scans**:
   - Create scanning policies for various assets (e.g., web servers, databases).
   - Conduct vulnerability scans across key systems.

3. **Configure Access Controls**:
   - Implement role-based access control (RBAC) for multiple teams managing scans.
   
4. **Tag Assets**:
   - Tag assets by criticality (e.g., high-priority servers) to focus scans on the most important resources.

5. **Analyze Results & Produce Reports**:
   - Use Nessus dashboards to view real-time data on vulnerabilities.
   - Generate comprehensive reports detailing findings, risk assessments, and recommended mitigations.

## Reports and Screenshots

Here are some screenshots and reports generated during the project:

### Nessus Dashboard:
![Nessus Dashboard](https://example.com/nessus-dashboard.png)

### Vulnerability Report:
![Vulnerability Report](https://example.com/vulnerability-report.png)

Download the full [Compliance Report](https://github.com/3BlackDot3/tenable-vulnerability-management/blob/main/reports/compliance-report.pdf).

## How to Run the Project

1. **Pre-requisites**:
   - Install [Nessus](https://www.tenable.com/products/nessus) on a server or VM.
   - Ensure you have network access to scan internal/external resources.

2. **Steps**:
   - Clone the repository:
     ```bash
     git clone https://github.com/3BlackDot3/tenable-vulnerability-management.git
     cd tenable-vulnerability-management
     ```
   - Follow the documentation in the `docs/` folder to set up Nessus and configure scans.

3. **Reporting**:
   - Use the provided scripts and tools in the repository to automate report generation and risk analysis.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
