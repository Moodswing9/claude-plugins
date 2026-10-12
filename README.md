<div align="center">

# 🧰 Moodswing9 Claude Code plugins

**Claude Code plugins for Dell EMC backup infrastructure — PowerProtect Data Manager, NetWorker and Data Domain**

[![Validate](https://img.shields.io/github/actions/workflow/status/Moodswing9/claude-plugins/validate.yml?branch=main&style=flat-square&label=marketplace)](https://github.com/Moodswing9/claude-plugins/actions/workflows/validate.yml)
[![License](https://img.shields.io/badge/license-MIT-22c55e?style=flat-square)](LICENSE)

</div>

---

## Install

Add the marketplace once:

```bash
claude plugin marketplace add Moodswing9/claude-plugins
```

Then install the plugins you want:

```bash
claude plugin install networker-ppdm@moodswing9
```

Inside Claude Code, the same works with `/plugin marketplace add Moodswing9/claude-plugins` and `/plugin install <name>@moodswing9`, or browse everything with `/plugin`.

To pick up new releases later, run `claude plugin marketplace update moodswing9`.

---

## Plugins

| Plugin | What you get |
|:---|:---|
| [**networker-ppdm**](https://github.com/Moodswing9/networker-ppdm) | Knowledge skill for NetWorker, PPDM and Data Domain, **13 slash commands** (health checks, SLA and executive reports, guided PPDM and NetWorker restores, restore monitoring, DR orchestration and planning, anomaly detection) and **2 agents** |
| [**backup-log-analyzer**](https://github.com/Moodswing9/backup-log-analyzer) | `/analyze-log` — severity, root causes and fix commands for PPDM, NetWorker, Data Domain, Veeam, syslog and Windows Event Log output |
| [**ppdm-es-troubleshooter**](https://github.com/Moodswing9/ppdm-es-troubleshooter) | `/es-diagnose` and `/ppdm-check` — PPDM Elasticsearch diagnosis and live cluster health |
| [**ppdm-watch**](https://github.com/Moodswing9/ppdm-watch) | `/ppdm-status` — AI briefing from ppdmwatch daemon logs |
| [**ppdm-capacity-planner**](https://github.com/Moodswing9/ppdm-capacity-planner) | `plan-capacity` skill — storage capacity forecasts with 80% and 95% breach projections |
| [**deck-generator**](https://github.com/Moodswing9/claude-deck-generator) | `/deck` and `/deck-remix` — PowerPoint and HTML presentations from any topic |

Each plugin's own README covers its requirements, such as Python for the backup scripts or environment variables for PPDM, NetWorker and Data Domain access.

---

## Related

- [ppdm-mcp-server](https://github.com/Moodswing9/ppdm-mcp-server) — 32 MCP tools for PPDM, NetWorker and Data Domain (`npx -y ppdm-mcp-server`)
- [ppdm-alert-bot](https://github.com/Moodswing9/ppdm-alert-bot) — PPDM and NetWorker alerts to Slack, Teams, PagerDuty and email

Portfolio: [moodswing9.github.io](https://moodswing9.github.io/)
