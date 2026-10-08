# Aryan Saini

Full-stack and AI engineer. Lead Engineer at [Laborhutt](https://laborhutt.com), UBC Computer Science.

I've spent four years building and running real software businesses: working directly with customers, shipping, and supporting things live. Today I lead a team of 3 engineers at Laborhutt, a moving and delivery marketplace, and I'm looking for my next full-time engineering role.

## Things I've built

| Project | What it is | Stack |
| --- | --- | --- |
| **Hypafy** | Event ticketing for university organizations. $500K+ in event revenue, 30+ campus organizations, offline-first gate scanning, fast native-feeling mobile apps | Next.js, Expo, Convex, Clerk, Stripe Connect |
| **Waitingroom** | Ticketing for a live music venue in Bangkok. 1M+ THB processed, Thai PromptPay payments | Next.js, Expo, Convex, Omise, Stripe |
| **Private Car Finder** | Agent harness for car dealerships: tool-using agents, human handoff, LLM-as-judge evals | Next.js, Convex, Vercel AI SDK, OpenRouter |
| **Qoreengine** | AI bid intelligence for a construction company. 8 bid boards, 1,000+ documents a day | TypeScript, AWS, Terraform, OpenAI |
| **Laborhutt** | Zero-downtime blue-green migration to Convex, checkout conversion from under 1% to 25%, full CI/CD for 7 apps | Next.js, React Native, Convex, Turborepo |

## Open source

- **[Postdraft](https://github.com/Aryan-Saini/postdraft)**: CLI that lets AI agents publish an HTML document and get a shareable link back. Originally forked from Theo's postplan, rebuilt on Convex. Also on npm as `postplan-aryan`
- **[Unified Inbox](https://github.com/Aryan-Saini/unified-inbox)**: searches Gmail, Slack and the web, and only replies after explicit confirmation
- **[Vorssaint Utils](https://github.com/vorssaint/vorssaint-utils)**: small contributor to one of my favorite macOS apps

## How I work

I run AI-assisted engineering like a small team:

- **Many agents, many models.** Claude Code, Codex and opencode, with the model picked per task for intelligence, taste and cost. Parallel agents work in isolated git worktrees so they never collide.
- **Review before merge.** Every change ships as a real PR with conventional commits, review bots, and a "council" of independent models (Claude, GPT and GLM) reviewing the diff before it lands.
- **Agent-ready codebases.** AGENTS.md domain glossaries, custom skills and architecture docs, so agents follow the same conventions as the engineers. At Laborhutt this cut agent token cost by 20%.
- **dragon, my home server.** A headless Arch Linux box that runs long agent jobs in tmux, reachable from anywhere over Tailscale, kept alive with systemd and Bash automation. I set up my roommate's Arch machine the same way.
- **One config everywhere.** The same rules, skills and MCP servers sync to every machine and every agent harness.

## What I'm learning

- **Agent harness design**: how models read intent, and how to structure tools, context and guardrails so agents do what you actually meant. Building my own benchmark for it, coming soon.
- **Infrastructure**: Kubernetes, distributed data systems (working through *Designing Data-Intensive Applications*), observability, Linux internals, networking and containers.

## Outside of code

Gym most days, new to climbing, and training for a triathlon.

## Contact

[LinkedIn](https://www.linkedin.com/in/saini-aryan) · aryansaini1005@gmail.com
