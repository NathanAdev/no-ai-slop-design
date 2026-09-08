# No AI Slop — Design Skill

Build or review frontend/UI work so it reads as deliberately designed, not AI-generated. Combines a bold-aesthetic-direction workflow, core design theory, and a categorized, current catalog of "AI slop" tells (default fonts, purple gradients, glassmorphism, icon-circle cards, chevron CTAs, placeholder content, and more) — each with the fix.

## How to install

### Claude (claude.ai, Claude Desktop, Cowork)

Upload the `.skill` file directly: **Settings → Capabilities → Skills → + Create skill**. It activates automatically whenever you're building, styling, or auditing a UI.

### Claude Code, Codex, Cursor, or another coding agent

Once this folder is pushed to a public GitHub repo, paste this into your agent:

```
Install the /no-ai-slop-design skill globally from https://github.com/<your-username>/no-ai-slop-design
```

Or install it directly with `npx`:

```
npx skills add <your-username>/no-ai-slop-design --skill no-ai-slop-design --global --yes
```

(`skills` is the [vercel-labs](https://github.com/vercel-labs/skills) CLI — supports Claude Code, Codex, Cursor, OpenCode, and 60+ other agents. `-g/--global` installs it once for every project instead of per-repo.)

### ChatGPT

No auto-loading skill mechanism exists here — paste the contents of `SKILL.md` into a Custom GPT's instructions, or into a Project's instructions/knowledge files. It'll follow the guidance, but you're responsible for bringing it into a conversation; it won't trigger itself on keywords the way it does in Claude.

## What's inside

- **`SKILL.md`** — the BUILD workflow (commit to a direction, set real tokens, then category-by-category guidance for type/color/layout/components/motion/copy) and the AUDIT workflow (quick 6-point check + how to flag findings)
- **`references/tells-catalog.md`** — the full checklist by category, with the fix for each and a false-positives section (so it's judgment, not a ban list)
