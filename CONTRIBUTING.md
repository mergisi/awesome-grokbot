# Contributing

Add a Grok Bot profile people can paste and run.

## Layout

```
bots/[category]/[slug]/
  PROFILE.md   # paste-ready name + prompt (YAML: name, category, integrations)
  SETUP.md     # first-message setup prompt (required)
  README.md    # setup prompt, connect list, first task, related bots
```

Then add one object to `bots.json` and one index row to [START.md](START.md).

Categories: `productivity`, `marketing`, `sales`, `ops`, `personal`, `development`.

## SETUP.md

One short block a new user pastes as the first message (or into Description). Must name the bot, say Name = PROFILE name and Description = PROFILE.md body, walk through Settings → Plugins for the listed integrations, point at the First task, and state the approval boundary (draft/research only).

## README.md

Title, one-line why, category. Then:

- ## The setup prompt — same text as SETUP.md in a copyable block, plus a link to SETUP.md
- ## Connect first — plugins from the PROFILE frontmatter
- ## First task — one starter message
- ## Profile — link to PROFILE.md
- ## Related bots — 2–3 others in the same category (relative links)

## PROFILE.md

YAML frontmatter (`name`, `category`, `integrations`) plus a paste-ready prompt.

## START.md

START.md is what a blank bot reads when the user sends the raw URL. If you add a bot, add one index row: name | one-line why | category | plugins | relative link to the folder. Do not paste PROFILE text into START.md. Do not add a copy-paste box.

To convert an OpenClaw or Hermes SOUL.md, send [CONVERT.md](CONVERT.md).

## Rules

- Unique one-line why in the README and in `bots.json`.
- Original profile and SETUP.md. Do not paste prompts from other directories.
- Do not add Mustafa team bots (AI2sql, Stripe, Mixpanel, GSC, GA, Growth, X Draft, LinkedIn, App Store, Uptime, GitHub Bot, Reddit Search, X Search, Manager).
- No npm, Docker, OpenClaw, or SOUL.md install steps.

## PR

Fork, add the folder (PROFILE.md + SETUP.md + README.md) + `bots.json` entry + one [START.md](START.md) index row, open a pull request.
