# MicrOrbit • ISO
###  — AI-First Cybersecurity Operations Platform

Built for the GoA Technology & Innovation Cybersecurity Division, Log Management Team.

---

## Modules

| Module | Covers |
|---|---|
| Overview | Live SIEM feed, threat metrics, GoA tool integrations, AI situation summary |
| Log Monitor | Real-time Sentinel ingestion, log source inventory, KQL AI assistant, CSV export |
| Threat Intelligence | Active threats, MITRE ATT&CK radar, threat feed status, AI threat briefings |
| Incident Response | Incident queue, ServiceNow-aligned tracking, AI playbook generator |
| Risk Register | STRA-aligned risk register, likelihood × impact scoring, treatment tracking |
| Compliance | FOIP, NIST CSF 2.0, GoA Cybersecurity Framework, AI audit evidence generator |
| Automated Insights | UEBA anomaly detection, predictive threat forecast, AI dataset analysis |
| Stakeholder Hub | Audience-tailored AI content generation for execs, partners, audit, staff |
| KPIs & Analytics | MTTD, MTTR, ingestion trends, AI forecasting, quarterly reports |
| AI Advisor | Conversational GoA ISO intelligence — Sentinel, FOIP, STRA, threats |
| User Manual | Full in-app documentation for every module |

---

## Deploy to Netlify (2 minutes)

### Option A — Drag and drop
1. Go to [netlify.com](https://netlify.com) and sign in
2. Click **Add new site → Deploy manually**
3. Drag the project folder into the deploy zone
4. Done — your URL is live instantly

### Option B — GitHub auto-deploy
1. Push this repository to GitHub
2. In Netlify: **Add new site → Import from Git**
3. Connect GitHub, select this repo
4. Build command: *(leave empty)*
5. Publish directory: `.`
6. Click **Deploy site**

Every push to `main` triggers a new deployment automatically.

---

## GoA Tool Alignment

- **Microsoft Sentinel** — SIEM ingestion, KQL queries, analytic rules
- **Defender for Endpoint** — Endpoint alerts, USB policy, threat signals
- **Entra ID (Azure AD)** — Identity events, conditional access, SSO logs
- **Azure Monitor** — Infrastructure diagnostics, Log Analytics workspace
- **ServiceNow ITSM** — Incident tracking (INC-xxxx), change management
- **Microsoft Purview** — Data classification, FOIP compliance
- **Intune MDM** — Device compliance state

---

## AI Features

All AI features use the Anthropic Claude API (`claude-sonnet-4-20250514`).

The platform includes a full GoA system prompt providing context about:
- GoA cybersecurity standards and STRA methodology
- FOIP retention requirements
- Microsoft Sentinel and Defender tooling
- GoA Zero Trust roadmap

For production deployment, proxy the Anthropic API through an **Azure API Management** instance or **Azure Function** to:
- Keep the API key server-side
- Enforce rate limiting
- Log AI interactions for audit purposes

---

## Standards Alignment

- GoA Cybersecurity Framework v2.1
- GoA STRA Methodology (GDS-SA-001)
- FOIP (Freedom of Information and Protection of Privacy Act, Alberta)
- NIST Cybersecurity Framework 2.0
- ISO/IEC 27001
- MITRE ATT&CK v14
- CISA Known Exploited Vulnerabilities (KEV)

---

*MicrOrbit • ISO — GoA T&I Cybersecurity Division*
