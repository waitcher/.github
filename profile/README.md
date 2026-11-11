# Waitcher

**Know when your site breaks, and why.**

[Waitcher](https://waitcher.dev) checks your websites, APIs and certificates on a schedule, and runs your API, browser and visual checks as monitors. Monitors live in a `waitcher.json` next to your code, and the CLI plans and deploys them from your terminal, CI or a coding agent. When a check fails you get an incident and a message in Slack, by email or through a webhook, and the run keeps its status, timing and failure reason.

## Get started

```sh
npx skills add waitcher/skills          # the agent skill for Claude Code, Codex and others
npm install -g @waitcher/cli@latest     # or the CLI on its own
```

Then ask your agent: "Use the waitcher skill to set up monitoring for this repository."

## Links

- [waitcher.dev](https://waitcher.dev): the product and a playground that runs in your browser without an account
- [Docs](https://waitcher.dev/docs/), also for coding agents ([llms.txt](https://waitcher.dev/llms.txt))
- [@waitcher/cli](https://www.npmjs.com/package/@waitcher/cli) on npm
- [waitcher/skills](https://github.com/waitcher/skills): the agent skill and the monitors of five real sites as examples
- [Pricing](https://waitcher.dev/pricing): free for 5 monitors
