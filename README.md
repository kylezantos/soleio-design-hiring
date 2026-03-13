# Soleio's Design Talent Playbook

An agent skill that turns [Soleio's design sourcing framework](https://x.com/soleio/status/2032284102322495604) into an interactive strategy tool.

Two modes. One framework.

## What it does

The skill acts as a strategic advisor — not a framework to read, but a consultant that thinks through the problem with you. It asks diagnostic questions, figures out your specific situation, and gives tailored recommendations.

**Hiring Mode** (`/soleio-design-hiring hire`) — For founders, hiring managers, and recruiters. Diagnoses your situation (what you're building, your design reputation, what you've tried), profiles your target designers, identifies your advantages and gaps, then recommends specific actions based on what will actually work for you.

**Designer Mode** (`/soleio-design-hiring designer`) — For designers looking to get hired by great companies. Assesses where you are now, researches your target companies, runs a gap analysis on your visibility and positioning, then builds a plan tied to your specific goals.

## The approach

Based on Soleio's core insight: the best designers don't respond to generic job postings. Most aren't even looking. You have to go where they are and be someone they want to talk to.

The skill doesn't present a menu of strategies — it diagnoses your situation and recommends what to prioritize. Under the hood, it draws on Soleio's sourcing channels, real case studies (Tom Johnson's path to Vercel, Profound's design page, Notion's iconic tweet, Julie Zhuo's hiring framework), and the "game film" model to give advice that's specific to you.

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

Based on [Soleio's sourcing framework](https://x.com/soleio/status/2032284102322495604), March 2026. Enriched with context from [Tom Johnson](https://x.com/tomjohndesign/status/1990811892139372899), [Julie Zhuo](https://x.com/joulee/status/1952386829287899374), [Profound](https://www.tryprofound.com/design), and [Notion](https://x.com/NotionHQ/status/1105905796095696897).
