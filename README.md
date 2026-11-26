# IAM & Cloud Security Automation (`iam-cloud-sec`)

Python automation scripts, KQL detection queries, and cloud governance utilities focused on **Identity and Access Management (IAM)**, **Identity Threat Detection and Response (ITDR)**, and **Azure Cloud Security Operations**.

---

## 🎯 Focus Areas
* **Identity Governance & Auditing:** Automated checks for stale accounts, privileged role assignments, and access drift in Microsoft Entra ID via Microsoft Graph API.
* **Identity Threat Detection & Response (ITDR):** Parsing sign-in telemetry and hunting for anomalous logins, impossible travel, token abuse, and privilege escalation.
* **SOC & Alert Enrichment:** Python scripts to normalize security logs, enrich suspicious IPs/indicators via threat intelligence APIs, and streamline incident triage.
* **Cloud Security & Policy-as-Code:** KQL hunting queries for Microsoft Sentinel and sanitized Conditional Access / RBAC configuration templates.

---

## 📂 Repository Structure
```text
iam-cloud-sec/
├── entra_governance/       # Python scripts for Entra ID & Graph API access audits
├── itdr_detections/        # Sign-in log anomaly parsers & Sentinel KQL hunting rules
├── soc_automation/         # Alert enrichment, IOC parsing & triage utilities
├── cloud_policies/         # Sanitized Conditional Access & RBAC templates
├── docs/                   # Triage runbooks, architecture notes & MITRE ATT&CK mappings
├── requirements.txt        # Python dependencies
└── README.md
```

---

## 🛠️ Tech Stack & Credentials
* **Languages & Querying:** Python, KQL (Kusto Query Language), SQL, PowerShell
* **Cloud & Security Platforms:** Microsoft Entra ID, Microsoft Sentinel, Microsoft Defender XDR, Microsoft Defender for Cloud, Microsoft Graph API
* **Certifications:** CompTIA CySA+ | CompTIA Security+ | Microsoft Certified: Azure Cloud and AI Security Engineer Associate (SC-500) | Microsoft Certified: Identity and Access Administrator Associate (SC-300)

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd iam-cloud-sec
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate        # macOS/Linux
   venv\Scripts\activate           # Windows
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure environment variables:**
   Store API keys and tenant credentials locally in a `.env` file (excluded via `.gitignore`—never commit secrets).

---

## ⚠️ Disclaimer
All scripts, queries, and policy templates in this repository are intended for educational, defensive security, and authorized auditing purposes only. Sample logs and tenant identifiers are anonymized.

---

## 📫 Connect
* **LinkedIn:** [Jordan Matthew Pauley, MPA, CySA+](https://www.linkedin.com/in/jordanmatthewpauley/)
* **GitHub:** [github.com/jordanpauley](https://github.com/jordanpauley)
