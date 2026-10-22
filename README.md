# First read

**Give your agent the link. Get back how a stranger meets your app.**

Can you see your own app the way a new customer does?

No. Nobody can. You know where everything is.

Your agent can. Give it the link, and it walks in cold: homepage, five seconds, laptop and phone, the way a stranger does. Then it writes down what it found.

One strength you can rely on.
One constraint in the way, and the smallest change that removes it.
One move to make this week, with people, not with the product.

Every finding carries its evidence. No number it didn't see.

The part we like most: the read ends with a move, not a list. One thing to do, and the count that tells you whether it worked.

## A real one

Here's the first run → [GreenLife, 22 October 2026](examples/greenlife-2026-10-22.md), in Codex, the model's words unedited.

It found a notification panel sitting on top of the first nudge on a phone, and measured the reading button at 1,025 px down on an 844 px screen. We built GreenLife. We hadn't seen it.

Before offering this to anyone, we ran it on our own site → [orchestra.hyperdrift.io/traction/first-read](https://orchestra.hyperdrift.io/traction/first-read)

## Install

The skill lives in `skills/first-read/`. Copy that folder where your agent reads skills:

| Client | Folder |
|---|---|
| Claude Code | `.claude/skills/first-read/` in your project, or `~/.claude/skills/` |
| Codex | `.agents/skills/first-read/` in your project, or `~/.codex/skills/` |
| Any client that supports [Agent Plugins](https://agent-plugins.org) | Load this repository's folder as a plugin |

Or one command:

```
npx skills add hyperdrift-io/first-read
```

Then ask:

```
Use the first-read skill on https://yourapp.example
```

## What it never does

No sign-in. No forms. No account. No number it didn't see. Your analytics stay yours; the read tells you what a next read could do with them.

## Why

Too many good apps never reach the people they were made for. Not because they're bad. Because nobody read them cold and said: here's the one thing in the way.

That's the read we give a founder before we work together. Now your agent can give it to you.

Want one from a person, with your private numbers and the next move prepared on a board? Introduce your app → [orchestra.hyperdrift.io/traction](https://orchestra.hyperdrift.io/traction?utm_source=first-read-skill&utm_medium=readme)

MIT. Made by [Orchestra](https://orchestra.hyperdrift.io).
