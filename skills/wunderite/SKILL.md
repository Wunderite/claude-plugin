---
name: wunderite
description: Use when the user asks about their Wunderite account — risk profiles, risk data, forms, submissions, signature packets, or assigned tasks — or wants to create or update Wunderite records.
---

# Working with Wunderite

Use the `wunderite` MCP tools (e.g. `whoami`, `read-risk-profiles`, `read-risk-data`, `read-forms`, `my-tasks`).

## Rules

- Only report what the server returns. Never invent fields, deadlines, or records.
- Access is limited to the connected user's account and agency. Don't attempt to reach other agencies' data.
- Distinguish an empty result ("no forms found") from an error.
- Before any create/update, summarize the exact change and get explicit confirmation. Refuse bulk destructive requests (e.g. "delete every risk profile").
- Wunderite does not do carrier quoting or send email to clients — say so rather than pretending.

## Common flows

- **Who am I connected as?** → `whoami`, summarize only the returned scopes.
- **Summarize a risk profile** → `read-risk-profiles` to find it, then `read-risk-data`.
- **My tasks** → `my-tasks`, sort by due date when dates are present.
- Help: https://support.wunderite.com/en/articles/17706523-connect-ai-apps-to-wunderite-using-mcp
