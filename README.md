# skills-sales-support

Claude / Agent **skills** library by **Poorvith M P**.

- Version: **v0.1**
- Last updated: **July 2026**
- License: **MIT**
- Skills in this repo: **11**

Part of the **[open-claude-skills](https://github.com/prvthmpcypher/open-claude-skills)** multi-repo hub.

## Install

### Claude Code
```bash
# copy one skill
cp -R skills/<skill-id> ~/.claude/skills/<skill-id>
# or project-local
cp -R skills/<skill-id> .claude/skills/<skill-id>
```

### Claude.ai
Zip a single `skills/<skill-id>` folder and upload via **Settings → Capabilities → Skills**.

## Skill index

| Skill ID | Title |
|----------|-------|
| `account-strategist` | Account Strategist |
| `analytics-reporter` | Analytics Reporter |
| `discovery-coach` | Discovery Coach |
| `executive-summary-generator` | Executive Summary Generator |
| `finance-tracker` | Finance Tracker |
| `legal-compliance-checker` | Legal Compliance Checker |
| `outbound-strategist` | Outbound Strategist |
| `pipeline-analyst` | Pipeline Analyst |
| `proposal-strategist` | Proposal Strategist |
| `sales-coach` | Sales Coach |
| `sales-engineer` | Sales Engineer |

## Structure

Each skill follows skill-creator conventions:

```text
skills/<skill-id>/
├── SKILL.md
├── references/NOTE.md   # empty tips for future progressive disclosure
└── assets/NOTE.md       # empty tips for future templates
```

## Author

Copyright (c) 2026 Poorvith M P
