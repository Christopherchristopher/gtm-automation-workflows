# GTM Automation Workflows

n8n workflows from my GTM engineering portfolio. Each workflow is exported as JSON and can be imported directly into n8n.

📂 **Full write-ups, screenshots and video walkthroughs:** [Notion portfolio link]

---

## Workflows

| Workflow | What it does | Stack |
|---|---|---|
| **Lead Lifecycle Orchestrator** | Syncs Clay-scored leads to HubSpot with dedupe, suppression, tier routing, retries and a dead-letter queue | n8n · Google Sheets · HubSpot · Slack |
| **Lead Lifecycle Digest** | Scheduled pipeline health report: lead volume and error rate posted to Slack | n8n · Google Sheets · Slack |
| **Real-Time Signal Monitoring** | Monitors target accounts for funding, hiring and partnership news | n8n · Serper API · Google Sheets |
| **Zendesk Ticket Triage** | AI classifies and prioritises new tickets, updates Zendesk and alerts Slack on critical issues | n8n · Zendesk · OpenAI · Slack |
| **Lead Intake and Scoring Router** | Validates, scores and routes inbound leads to HubSpot or nurture | n8n · Webhook · HubSpot · Google Sheets |
| **Clay → HubSpot Sync** | Pushes Clay company data and AI prospect briefs to HubSpot via API | n8n · HubSpot API |

---

## How to import
1. Download the `.json` file
2. In n8n, create a new workflow, click **⋯**, then **Import from file**
3. Add your own credentials (none are included)

---

## About me
Data scientist turned GTM Engineer, based in the UK.
💼 [LinkedIn URL]
