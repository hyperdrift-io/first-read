# First read

**Give your agent a URL. Get back how your app reads to a stranger.**

You know your product too well to see it cold. A new customer lands on the
homepage, gives it five seconds, and either finds the way in or leaves. A first
read is that walk, written down: one strength you can rely on, one constraint in
the way, and one move to make this week with people rather than with the
product. Every finding carries its evidence, and the read says what it could
not see.

It is the method we use before working with a founder. Here it is as an
[Agent Skill](https://agentskills.io), so your own agent can run it on your app
today.

## What you get

```
App: https://yourapp.example
Read on: 22 October 2026
Read from: public pages only, as a new visitor meets them, laptop and phone

Strength        one thing a stranger can check, and why it matters
Constraint      the one thing in the way, and the smallest change that removes it
Next customer move
                one move this week, the count that shows it worked,
                how to read a miss, and how to measure it
What this read could not see
```

A published example, run on our own site first:
[orchestra.hyperdrift.io/traction/first-read](https://orchestra.hyperdrift.io/traction/first-read).

## Real output

[GreenLife, 22 October 2026](examples/greenlife-2026-10-22.md): run in Codex
from a folder holding nothing but the skill, the model's words unedited. It
found a notification panel covering the first nudge on a phone, measured where
the reading button sits, and proposed a five-person test with a success count.

## Install

The skill lives in `skills/first-read/`. Copy that folder where your agent reads
skills:

| Client | Folder |
|---|---|
| Claude Code | `.claude/skills/first-read/` in your project, or `~/.claude/skills/` |
| Codex | `.agents/skills/first-read/` in your project, or `~/.codex/skills/` |
| Any client that supports [Agent Plugins](https://agent-plugins.org) | Load this repository's folder as a plugin |

Then ask:

```
Use the first-read skill on https://yourapp.example
```

## What it never does

It reads public pages only. It never signs in, never submits a form, never
creates an account, never states a number it did not see. Your analytics stay
yours; the read tells you what a next read could do with them.

## The door

The read ends with one line: introduce your app, and a link to Traction, where
a person reads it with the private numbers and prepares the next move on a
board. That is the only thing it asks.

MIT. By [Hyperdrift](https://hyperdrift.io).
