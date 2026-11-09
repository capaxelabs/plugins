# Capaxe Labs plugins

Claude Code plugins for our hosted MCP servers. Each one connects Claude to a service you sign in to with OAuth. Nothing runs on your machine.

| Plugin | What it does | Repo |
| --- | --- | --- |
| **beefi** | SEC EDGAR data for US public companies: financials, insider trades, 13F holdings, filings and macro | [beefi-ai-mcp](https://github.com/capaxelabs/beefi-ai-mcp) |
| **opskitty** | Uptime checks for sites and APIs, status pages, cron heartbeats, Lighthouse and SEO audits | [opskitty-mcp](https://github.com/capaxelabs/opskitty-mcp) |
| **raechly** | Cold email from your agent: mailboxes, warmup, lead search, campaigns, replies and deals | [raechly-mcp](https://github.com/capaxelabs/raechly-mcp) |

## Install

Add the marketplace once:

```bash
claude plugin marketplace add capaxelabs/plugins
```

Then install the ones you want:

```bash
claude plugin install beefi@capaxe
claude plugin install opskitty@capaxe
claude plugin install raechly@capaxe
```

Run `/mcp` in Claude Code and sign in to each one.

Using Claude.ai, ChatGPT, Cursor or VS Code instead? Each plugin repo has setup steps for those clients.

## License

MIT
