# MicrOrbit • ISO
### AI-First Cybersecurity Operations Platform

---

## Modules

| Module | What it does |
|---|---|
| Overview | Live metrics, SIEM feed, threat summary, AI situation summary |
| Log Monitor | Simulated SIEM log stream, source inventory, AI query generator, CSV export |
| Threat Intelligence | Active threat queue, MITRE ATT&CK radar, AI threat briefings |
| Incident Response | Incident queue, AI playbook/RCA generator, new incident form |
| Risk Register | Likelihood × impact scoring, add/filter risks, AI treatment advisor |
| Compliance | Framework status tracker, AI audit evidence generator |
| Automated Insights | UEBA anomaly chart, threat forecast, AI dataset analysis |
| Stakeholder Hub | AI-tailored materials for exec, audit, partners, staff |
| KPIs & Analytics | MTTD, MTTR, ingestion trends, AI forecast, quarterly reports |
| AI Advisor | Conversational security AI with chat history |
| Reports | HTML reports for all areas, print-to-PDF, AI report generator |
| Settings | API key management, org config, data source info |
| User Manual | In-app documentation for every module |

---

## Data source

**All data is simulated.** No real security systems are connected. The log stream, threats, incidents, risk scores, and KPI charts are pre-populated with realistic demo values. Connect real data sources via the Settings page connectors.

---

## AI features

AI features require an Anthropic API key:
1. Get a key at [console.anthropic.com](https://console.anthropic.com)
2. Open the app → Settings → paste your key → Save
3. Click "Test connection" to verify

The key is stored in `localStorage` (browser only). For production, proxy API calls through a serverless backend to keep the key server-side.

---

## Deploy to Netlify

### Drag and drop (fastest)
1. Go to [netlify.com](https://netlify.com)
2. Click **Add new site → Deploy manually**
3. Drag the project folder into the deploy zone
4. Done — live URL in seconds

### GitHub auto-deploy
1. Push this folder to a GitHub repo
2. Netlify → **Add new site → Import from Git**
3. Connect GitHub, select the repo
4. Build command: *(empty)* — Publish directory: `.`
5. Deploy — every push to `main` auto-redeploys

---

*MicrOrbit ISO — v1.0.0*
