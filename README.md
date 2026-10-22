# First read

First read is an Agent Skill. Give your agent the link to your app and it reads it the way a new customer meets it: public pages only, laptop and phone, five seconds on the homepage and then the path to the first useful result.

You get back:

- one strength you can rely on
- one constraint in the way, and the smallest change that removes it
- one move to make this week, with people, not with the product, and the count that shows it worked
- what the read could not see

Every finding carries its evidence: the page, the quote, the measurement. It states no number it did not see.

## The first run

GreenLife, 22 October 2026, run in Codex, the model's words unedited: [examples/greenlife-2026-10-22.md](examples/greenlife-2026-10-22.md)

It found a notification panel covering the first nudge on a phone and measured the reading button at 1,025 px down on an 844 px screen. We built GreenLife. We hadn't seen it.

We ran the same read on our own site before offering it to anyone: [orchestra.hyperdrift.io/traction/first-read](https://orchestra.hyperdrift.io/traction/first-read)

## Install

```
npx skills add hyperdrift-io/first-read
```

Or copy `skills/first-read/` where your agent reads skills:

| Client | Folder |
|---|---|
| Claude Code | `.claude/skills/first-read/` in your project, or `~/.claude/skills/` |
| Codex | `.agents/skills/first-read/` in your project, or `~/.codex/skills/` |
| Any client that supports [Agent Plugins](https://agent-plugins.org) | load this repository's folder as a plugin |

Then ask:

```
Use the first-read skill on https://yourapp.example
```

## What it never does

No sign-in, no forms, no account, no analytics. Your numbers stay yours. The read says what a next read could do with them.

## Why

A founder knows their product too well to see it cold. This is the read we give a founder before we work together. Now your agent can give it to you.

If you want one from a person, with your private numbers and the next move prepared on a board, introduce your app: [orchestra.hyperdrift.io/traction](https://orchestra.hyperdrift.io/traction?utm_source=first-read-skill&utm_medium=readme)

MIT. Made by [Orchestra](https://orchestra.hyperdrift.io).
