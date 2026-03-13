# Soleio's Design Talent Playbook

A [Claude Code](https://claude.ai/claude-code) skill that turns [Soleio Cuervo's design sourcing framework](https://x.com/soleio/status/2032284102322495604) into an interactive strategy tool.

Two modes. One framework.

## What it does

**Hiring Mode** (`/soleio-design-hiring hire`) — For founders, hiring managers, and recruiters sourcing design talent. Walks you through identifying your role, profiling target designers (or building a candidate persona from references), and generates a sourcing strategy across six channels: social sourcing, community presence, opinionated job pages, referral nodes, recruiters, and conversation openers.

**Designer Mode** (`/soleio-design-hiring designer`) — The framework flipped. For designers positioning themselves to get hired by great companies. Helps you define your targets, build a visibility strategy based on the "game film" model, and create a positioning plan.

## The framework

Based on Soleio's core insight: the best designers don't respond to generic job postings. Most aren't even looking. You have to go where they are and be someone they want to talk to.

The skill operationalizes his six sourcing channels:

1. **Social sourcing** — Watch game film on X. Follow high-signal communities around cutting-edge design tools.
2. **Community presence** — Host events tailored to the talent you want. Fish from a barrel of your own making.
3. **Job page as product** — Create an opinionated, memorable design page. A great one works while you sleep.
4. **Referral nodes** — Cultivate 3-5 people who know great designers and think of you when talent moves.
5. **Recruiters (selective)** — A mediocre recruiter is worse than none. Find credible ones.
6. **The conversation opener** — "If I could guarantee you interviews with any 2-3 companies, which would they be and why?"

Enriched with real case studies: Tom Johnson's cold-DM-to-Vercel pipeline, Profound's design page, Notion's "Designer Who Can Code" tweet, Julie Zhuo's hiring advice, and the content-creator recruiter model (Ridd, DesignerTom).

## Install

### One command (all agents)

```bash
npx skills add kylezantos/soleio-design-hiring
```

Auto-detects your installed agents and installs to each. Works with Claude Code, Codex, OpenClaw, Cursor, Gemini CLI, Windsurf, OpenCode, and [35+ more](https://github.com/vercel-labs/skills).

### Target specific agents

```bash
npx skills add kylezantos/soleio-design-hiring -a claude-code
npx skills add kylezantos/soleio-design-hiring -a codex -a openclaw
```

### Manual install

Copy `SKILL.md` into your agent's skills directory:

| Agent | Path |
|-------|------|
| Claude Code | `~/.claude/skills/soleio-design-hiring/` |
| Codex | `~/.codex/skills/soleio-design-hiring/` |
| OpenClaw | `~/.openclaw/skills/soleio-design-hiring/` |
| Cursor | `~/.cursor/skills/soleio-design-hiring/` |
| Gemini CLI | `~/.gemini/skills/soleio-design-hiring/` |
| Windsurf | `~/.codeium/windsurf/skills/soleio-design-hiring/` |
| OpenCode | `~/.config/opencode/skills/soleio-design-hiring/` |
| Perplexity Computer | Add via the Skills UI in the Computer tab (SKILL.md compatible) |

Or clone:

```bash
git clone https://github.com/kylezantos/soleio-design-hiring.git ~/.claude/skills/soleio-design-hiring
```

## Usage

```
/soleio-design-hiring hire
/soleio-design-hiring hire -- I'm a founder building an AI product and need a product designer
/soleio-design-hiring designer
/soleio-design-hiring designer -- I'm a product designer targeting AI startups like Cursor and Perplexity
```

## Attribution

Based on [Soleio Cuervo's sourcing framework](https://x.com/soleio/status/2032284102322495604), March 2026. Enriched with context from [Tom Johnson](https://x.com/tomjohndesign/status/1990811892139372899), [Julie Zhuo](https://x.com/joulee/status/1952386829287899374), [Profound](https://www.tryprofound.com/design), and [Notion](https://x.com/NotionHQ/status/1105905796095696897).
