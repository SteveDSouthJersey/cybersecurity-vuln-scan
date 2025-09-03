Cybersecurity Vulnerability Scan Project
Overview

This project was constructed by using the following hands-on vulnerability assessment tools:

Nessus Essentials (for vulnerability scanning)

Metasploitable 2 (an intentionally vulnerable Linux VM)

The intention of this project is to show my ability to set up labs, run scans, and present reports as part of my cybersecurity portfolio
the complete goals for the project are as follows:
- Install and configure Nessus Essentials in a controlled test environment
- Run a vulnerability screening using Metasploitable on VirtualBox
- Export results in CSV and HTML
- Have both reports for technical and non-technical analyzing

Repository structure:
cybersecurity-vuln-scan/
│

├── README.md                        # Project overview (this file)

├── artifacts/                       # Raw scan results (CSV/HTML)

│   ├── Metasploitable2_Scan.csv

│   └── Metasploitable2_Scan.html

├── report/                          # Written assessment/report

│   └── Vulnerability-Assessment-Report.md

└── scripts/                         # Optional helper scripts
    └── summarize_critical_high.py
Steps to open:
-Open artifact/ folder to view data
CSV for structured data
HTML for formatted report
disclaimer: This project was created and performed in a controlled environment using a virtual machine.
