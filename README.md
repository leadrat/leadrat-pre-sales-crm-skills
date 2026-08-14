# LeadRat MCP Claude Skills

A collection of Claude Skills built on the **LeadRat MCP Prompt Library** for pre-sales CRM analysis. These skills give Claude structured, repeatable analysis workflows for sales, marketing, agent performance, funnel diagnostics, and revenue reporting — all powered by live LeadRat data via the LeadRat MCP connector.

🌐 Learn more about LeadRat MCP at [mcp.leadrat.com](https://mcp.leadrat.com)

---

## Prerequisite

The **LeadRat MCP connector** must be connected in Claude before using any of these skills. Without it, Claude cannot query your LeadRat CRM data.

- **Claude.ai**: Go to **Settings → Integrations** and connect LeadRat MCP.
- **Claude Code**: Add the LeadRat MCP server to your `.mcp.json` configuration.

---

## Installation

### Claude Code

```bash
# Clone this repository
git clone https://github.com/leadrat/leadrat-pre-sales-crm-skills.git

# Copy the skill folder(s) you want into Claude's skills directory
cp -r leadrat-pre-sales-crm-skills/sales-performance-gap-analysis ~/.claude/skills/
```

Repeat the `cp` command for each skill you want to install, or copy all at once:

```bash
cp -r leadrat-pre-sales-crm-skills/*/ ~/.claude/skills/
```

### Claude.ai (Web)

1. Go to **Settings → Capabilities → Skills**.
2. Click **Add Skill** and upload the desired skill folder, or point Claude.ai at this repository.

---

## Available Skills

| Skill Folder | Description |
|---|---|
| `sales-performance-gap-analysis` | Evaluates overall sales performance vs benchmark across every funnel stage and identifies gaps, root causes, and recommended focus areas. |
| `marketing-performance-gap-analysis` | Analyses which marketing sources and campaigns generate quality leads and revenue, highlighting best and underperforming channels. |
| `agent-performance-productivity` | Measures how effectively each agent handles and converts assigned opportunities and surfaces coaching areas. |
| `conversion-performance-analysis` | Tracks stage-wise lead conversion and drop-off through the sales journey to identify the highest-impact conversion gaps. |
| `project-marketing-fit-analysis` | Determines whether the right marketing sources are generating quality demand for each project. |
| `funnel-performance-bottleneck-analysis` | Identifies where leads get stuck or lost in the funnel and pinpoints the biggest bottlenecks. |
| `followup-sales-execution-gap-analysis` | Reveals whether the sales team is properly working available opportunities by analysing activity, response, and follow-up gaps. |
| `management-action-improvement-plan` | Turns multi-dimensional performance insights into a prioritised action plan with expected business impact. |
| `revenue-performance-gap-analysis` | Understands revenue drivers, decline areas, and growth opportunities across projects, sources, and agents. |
| `prompt-library` | Reference library of 160 drill-down prompts organised by category for deeper LeadRat MCP analysis. |

---

## License

MIT — see [LICENSE](LICENSE) if present.

## Contributing

Pull requests are welcome. Please open an issue first to discuss significant changes.
