# n8n-workflow-automations


> **Sample / demo builds** — example n8n workflows showing common automation patterns for small businesses. Built for learning and demonstration, not production use.


## What's inside


| Workflow | What it demonstrates |
|---|---|
| `workflows/lead-capture-to-sheets.json` | Webhook trigger → validate lead → append row to Google Sheets |


## Patterns covered


- **App integrations** — connecting webhooks, email, Slack, and WhatsApp Cloud API nodes
- **Google Sheets pipelines** — appending, updating, and looking up rows as a lightweight CRM
- **Scheduled jobs** — cron triggers for daily digests, reminders, and cleanup tasks
- **Error handling** — IF nodes and error branches so failed runs notify instead of silently dropping data


## How to use a sample workflow


1. In n8n, go to **Workflows → Import from file** and choose the JSON file in `workflows/`.
2. Open the workflow and set your own credentials (Google Sheets, SMTP/Slack/WhatsApp).
3. Adjust sheet names, email addresses, and schedules to match your setup.
4. Activate the workflow.


## Notes


- These are **simplified teaching examples**: credentials are placeholders, and the Sheets/WhatsApp steps need your own accounts and API keys.
- n8n workflow JSON is portable — export/import via the n8n UI or the `n8n export:workflow` CLI.
- For production, add proper secrets management, retry policies, and monitoring.


## Tech


n8n · Webhooks · Google Sheets · Cron/Schedule triggers · Slack / SMTP / WhatsApp Cloud API
