# -secops-detection-response-lab
Enterprise-style Security Operations lab showcasing detection engineering, threat hunting, and automated incident response using Microsoft Sentinel, Defender, and SIEM/SOAR workflows.

secops-detection-lab/
│
├── README.md
├── architecture/
│   └── secops-architecture.png
│
├── detections/
│   ├── mfa_fraud.kql
│   ├── impossible_travel.kql
│   ├── suspicious_oauth_app.kql
│   ├── lateral_movement_smb.spl
│
├── automation/
│   ├── sentinel_playbook_email.json
│   ├── isolate_endpoint_logicapp.json
│
├── threat-hunting/
│   ├── azure_ad_hunting_queries.kql
│   ├── endpoint_hunting_scenarios.md
│
├── incident-response/
│   ├── phishing_playbook.md
│   ├── ransomware_playbook.md
│
├── dashboards/
│   ├── sentinel_workbook.json
│
├── metrics/
│   ├── kpi_definitions.md
│
├── scripts/
│   ├── log_ingestion.ps1
│   ├── alert_enrichment.py
│
└── docs/
    ├── setup-guide.md
    ├── use-cases.md
