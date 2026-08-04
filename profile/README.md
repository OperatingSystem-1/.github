<div align="center">

<img src="https://mitosislabs.ai/mitosis-app-icon.svg" width="96" alt="Mitosis Labs" />

# Mitosis Labs

**AI's adoption problem isn't intelligence. It's interfaces and data. We fix both.**

</div>

---

Businesses aren't seeing returns on AI because their data is disorganized and their tools are stuck behind clunky, half-finished interfaces. So agents guess, hallucinate, and burn tokens re-reading everything — and owners stop trusting the output.

We fix both halves:

- **Cortex — the AI's better brain.** Connects to what a business already uses — email, WhatsApp, CRM, documents — so any agent answers from real records instead of guessing. Every answer cites its source. Private and end-to-end encrypted.
- **Yappy — the AI's better body.** Simple, reliable AI interfaces — speech to text, computer use — across desktop and mobile, with no privacy tradeoff. Built on Cortex.

**Measured, not promised:** 98% fewer hallucinations, third-party verified · a tenth of the token spend · ranked first on the public memory benchmark at 91.7% · every answer cites its sources. [Read the research →](https://mitosislabs.ai/research)

## Get started

```bash
npm install -g @mitosislabs/sdk   # the `mi` CLI
mi login                          # browser OAuth
mi cortex ask "<question>"        # answers that cite their sources
```

[![npm downloads](https://img.shields.io/npm/dt/@mitosislabs/sdk?logo=npm&label=downloads&style=flat-square)](https://www.npmjs.com/package/@mitosislabs/sdk)

**Already running an agent?** Connect it to its user's memory:

```bash
npx skills add OperatingSystem-1/mitosis-memory-skills
```

Or point any MCP client at `https://mitosislabs.ai/api/mcp`.

## Open source

| | |
|---|---|
| [`mitosis-memory-skills`](https://github.com/OperatingSystem-1/mitosis-memory-skills) | Connect any agent to a user's private Mitosis memory — cited retrieval, durable write-back |
| [`mitosis-agent-configs`](https://github.com/OperatingSystem-1/mitosis-agent-configs) | Drop-in agent configs: AGENTS.md, .cursorrules, Claude Code instructions, MCP client config |
| [`local-benchmark`](https://github.com/OperatingSystem-1/local-benchmark) | Measure what your AI coding agent wastes — hallucinated paths, re-reads, retry loops — from your own session logs |
| [`mcp-git-coord`](https://github.com/OperatingSystem-1/mcp-git-coord) | MCP server that coordinates multiple coding agents working on the same codebase |
| [`colony-benchmark`](https://github.com/OperatingSystem-1/colony-benchmark) | Benchmark suite for autonomous multi-agent performance — one directive, agents self-organize |
| [`thedeclaration`](https://github.com/OperatingSystem-1/thedeclaration) | The Declaration of Intelligence — signed in public, by pull request |
| [`agent-wall-of-fame`](https://github.com/OperatingSystem-1/agent-wall-of-fame) | Where agents present their best work — weekly demos, challenges, and votes |

## Reading

- [mitosislabs.ai](https://mitosislabs.ai)
- [Documentation](https://mitosislabs.ai/docs)
- [Research](https://mitosislabs.ai/research)
- [Research notes](https://mitosislabs.ai/aixiv)
- [Agent Wall of Fame](https://mitosislabs.ai/wall-of-fame)

## Contact

[hello@mitosislabs.ai](mailto:hello@mitosislabs.ai) · [security@mitosislabs.ai](mailto:security@mitosislabs.ai)

---

<sub>[Request Demo](https://cal.com/mitosis-alex/30min) · [Privacy Policy](https://mitosislabs.ai/privacy) · [Terms of Service](https://mitosislabs.ai/terms)</sub>
