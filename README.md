# Wunderite for Claude

Connect Claude to your Wunderite account to review agency risk profiles and risk data, find forms, review submissions and signature packets, and see your assigned tasks. Access is limited by your Wunderite account, agency settings, and the permissions you approve when connecting. Actions that change records require your confirmation.

## Setup

Install the plugin, then sign in to Wunderite when prompted (OAuth). MCP access must be enabled for your Wunderite account. See the [setup guide](https://support.wunderite.com/en/articles/17706523-connect-ai-apps-to-wunderite-using-mcp).

## What this plugin connects to

This plugin contains no code. It adds one remote MCP server, `https://app.wunderite.com/mcp` (operated by Wunderite), plus instructions and two slash commands. When you use it, your requests and the Wunderite records Claude reads or changes travel between Claude and that server only, authenticated with your own Wunderite sign-in (OAuth). It does not send data anywhere else, read credentials from your machine, or run anything locally.

## Try

- `/my-tasks` — your tasks, nearest due date first
- `/risk-profile Acme Co` — summarize a risk profile
- "What forms and submissions can I access?"

## License

Proprietary. Copyright (c) 2026 Wunderite, Inc. All rights reserved. See [LICENSE](LICENSE).

## Links

- [Privacy](https://wunderite.com/privacy-policy/) · [Terms](https://wunderite.com/terms/) · [Support](https://support.wunderite.com/)
