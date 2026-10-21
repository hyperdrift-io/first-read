# First read: material for the README

Not the public README. Yann writes the public words from this sheet; the facts
below are verified as of 22 October 2026. Replace this file with the README
before the repository goes public.

## What the skill does (facts)

- Takes one URL. Optionally who the app is for and what the founder wants next.
- Reads public pages only, the way a new visitor meets them, at laptop width and
  at phone width (390 px). Notes how far down the first action sits.
- Looks through six lenses: the promise, the path to value, the proof, being
  found, measurement, reliability.
- Returns one strength, one constraint with the smallest change that removes it,
  one customer move for the week with a success count and a way to read a miss,
  and what the read could not see. Every finding carries its evidence: page,
  quote, measurement.
- Dates the read. Says what was private and what a next read could do with it.
- Ends with one door: "Introduce your app" and the Traction link, tagged
  `utm_source=first-read-skill&utm_medium=agent`. No reply time, no price, no
  second link.

## What it never does

- Sign in, submit a form, create an account, run a trial.
- Touch analytics. State a number it did not see.

## Origin

- It is the method Hyperdrift runs before working with a founder.
- It was run on Orchestra's own site first, on 6 October 2026, before being
  offered to anyone: https://orchestra.hyperdrift.io/traction/first-read
- Why it had to exist: Yann's to say.

## Install (verified paths)

| Client | Folder |
|---|---|
| Claude Code | `.claude/skills/first-read/` in a project, or `~/.claude/skills/` |
| Codex | `.agents/skills/first-read/` in a project, or `~/.codex/skills/` |
| Agent Plugins clients | load the repository folder as a plugin (`plugin.json` at the root) |

Prompt that works: `Use the first-read skill on https://yourapp.example`

## Real output (facts from the run)

- Run in Codex on 22 October 2026 from a folder holding nothing but the skill.
- App: GreenLife, a Hyperdrift app. 334 words. The model's words, unedited:
  [examples/greenlife-2026-10-22.md](examples/greenlife-2026-10-22.md)
- Findings new to us: a floating "Turn on notifications" panel covers part of
  the first nudge at 390 px; the reading button sits 1,025 px down on an 844 px
  screen (878 px on the laptop).
- Proposed move: five people who want a simpler daily life open it on their
  phones; success when at least three of five try a nudge and ask for another.

## Links and metadata

- Published example: https://orchestra.hyperdrift.io/traction/first-read
- Door: https://orchestra.hyperdrift.io/traction?utm_source=first-read-skill&utm_medium=agent
- Agent Skills spec: https://agentskills.io · Agent Plugins spec: https://agent-plugins.org
- Licence: MIT. Author: Hyperdrift, https://hyperdrift.io
- GitHub repository description, 350 characters at most: currently a factual
  placeholder, to rewrite with the README.
- `plugin.json` description, shown by plugin clients: currently a factual
  one-liner, to confirm or rewrite.

## Shape of the public README, if useful

Bold one-liner · the moment a founder recognises · what you get (the output
block) · install · what it never does · real output · the door · licence line.
No length limit. Standup's README is the house precedent for shape only.
