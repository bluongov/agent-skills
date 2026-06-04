# agent-skills

[![skills.sh](https://skills.sh/b/bluongov/agent-skills)](https://skills.sh/bluongov/agent-skills)

A small collection of [agent skills](https://agentskills.io) for AI coding agents (Claude Code, opencode, Codex, Gemini CLI, and compatible tools).

## Skills

### `no-glaze`
Kills AI sycophancy. Turns your agent from an agreeable assistant into a blunt advisor: it challenges before it agrees, tags every claim with a confidence level (`[Certain]` / `[Likely]` / `[Guessing]`), disagrees with structure, leads with the uncomfortable answer, and holds its position under pressure instead of caving. Bans reflexive phrases like "you're absolutely right" and "great question."

### `spatial-thinker`
A communication-shaping persona for users who think natively in 3D / spatial-geometric terms. Reframes explanations as maps, dependency graphs, and architectural flythroughs instead of flat linear prose, and keeps the exchange dense and direct. Works out of the box; an optional persona block can pin it to a specific user.

## Install

Install all skills from this repo:

```bash
npx skills add https://github.com/bluongov/agent-skills
```

Or pick one:

```bash
npx skills add https://github.com/bluongov/agent-skills --skill no-glaze
npx skills add https://github.com/bluongov/agent-skills --skill spatial-thinker
```

## Pairing

`no-glaze` and `spatial-thinker` compose well: `no-glaze` governs *how honest* the agent is, `spatial-thinker` governs *how it structures* what it says.

## License

MIT
