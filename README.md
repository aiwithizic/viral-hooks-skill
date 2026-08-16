# Viral Hooks — a free Claude skill

Teach your Claude to write scroll-stopping hooks for TikTok, Reels, and Shorts.

It works by remixing the structures of **227 real hooks that each earned 200,000+
views** (many in the millions), scraped from top short-form creators and tagged by
pattern. You give it your topic, it gives you 6-10 hooks built on structures that
already won.

## Install (2 minutes)

**Claude Code (terminal or VS Code):**

1. Download or clone this folder
2. Copy it into your skills directory:

```
cp -r viral-hooks-skill ~/.claude/skills/viral-hooks
```

3. In any Claude Code session, ask: *"give me 10 hooks for a video about ___"*

**claude.ai (web/desktop):** open Settings, then Capabilities, and upload this
folder as a skill (zip it first if asked).

## Use it like this

> "Give me 10 hooks. Topic: meal prepping for night-shift nurses. Niche: nursing life."

You'll get hooks across different patterns (negative framing, number-led, gift,
curiosity...), each with the view count of the structure it was remixed from.

## What's in the box

- `SKILL.md` — the instructions your Claude follows: the remix method, the
  pattern taxonomy, and honesty rules (no bait, no overpromising)
- `hooks.json` — the database: hook text, views, creator, pattern tag

## Honest notes

- Hooks are drawn from public video captions/titles of high-performing posts;
  view counts were recorded at scrape time (August 2026) and only 200k+ made the cut.
- A hook only works if the video delivers what it promises. The skill will tell
  you that too.

Free, no email wall, no catch. Built by Izic — one practical AI tip a week at
[aiwithizic.com](https://www.aiwithizic.com). Found it useful? That's how you say thanks.
