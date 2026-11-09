# Obi CLI

Obi is an AI Search Employee. It learns your ICP, asks AI the questions your buyers ask, and writes the missing pieces that get your product recommended. This repository distributes the Obi CLI and its Skill, which run inside the coding agent you already use. Built for founders, GTM teams and marketing teams.

## Install

Node.js 22 or later is required.

```bash
npm i -g @hireobi/cli
obi skill install
```

Then open a new chat in your agent and call Obi:

| Agent | Call Obi with |
|---|---|
| Claude Code, Cursor | `/obi` |
| Codex | `$obi`, or Obi in the skills picker |

Obi asks which website to work on, then starts. The Skill also works in Windsurf, GitHub Copilot, Gemini CLI, Cline, Amp and OpenCode, and the CLI in any terminal: run `obi` to see the welcome, `obi --help` for every command.

## What Obi does

It learns **your ICP**, finds **the missing pieces** that get AI to recommend you, and **does the work end to end**. Results in weeks, free to start.

- **ICP-Based AI Search.** Every strategy targets the buyers who sign.
- **Contextual Buyer Prompts.** It asks AI the questions your buyers ask, in their own words.
- **Missing-Piece Content.** It writes what AI can't find elsewhere, so it cites you fast.

Obi measures answers on ChatGPT, Gemini and Google AI Overviews, and on Claude and Perplexity as add-ons. As the Agent Search Employee, it checks what AI crawlers and agents can read on your site and writes what agents read before they choose. The whole product: https://github.com/hireobi

## How it works, and what leaves your machine

- **Your agent does the thinking.** Obi researches and writes with your agent's model and tools, on the plan you already pay for. It reads the files a task needs only with your agreement.
- **Obi's servers measure.** They keep your account, ask the AI engines the buyer questions you approved, and store the measured answers.
- **You approve every page.** Every page Obi writes is a draft until you approve it. A plan never publishes, posts or buys anything on its own.
- **Your sign-in stays local.** The CLI keeps its connection in your system's credential store, or in a protected file where none exists. `obi doctor` says which; `obi logout` signs you out.

## Plans

Free: 10 questions on ChatGPT and Gemini, one scan a month. Core pack: 25 reviewed questions on ChatGPT, Gemini and Google AI Overviews, scanned weekly, $20 a month. Every plan: https://hireobi.com/pricing.md

## Check, update, remove

```bash
obi --version     # the installed version
obi doctor        # where the connection is stored; sends no request
obi logout        # signs out on this machine
npm uninstall --global @hireobi/cli
```

## Verify a download

Each [release](https://github.com/hireobi/cli/releases) lists the SHA-256 digest of its archive.

## Security

Report a vulnerability privately: [Report a vulnerability](https://github.com/hireobi/cli/security/advisories/new). What to expect and what is in scope: [SECURITY.md](https://github.com/hireobi/.github/blob/main/SECURITY.md).

## License

The CLI and Skill are distributed under the [Heysurface CLI License](LICENSE).

## Links

- Website: https://hireobi.com
- For AI agents: https://hireobi.com/agents.md
- Facts for AI assistants: https://hireobi.com/ai-instructions.md
- Every entity around Obi: https://hireobi.com/entity-map.md
- Obi on GitHub: https://github.com/hireobi
