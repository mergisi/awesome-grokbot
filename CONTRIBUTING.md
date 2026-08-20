# Contributing

Add a Grok Bot profile people can paste and run.

## Layout

```
bots/[category]/[slug]/
  PROFILE.md   # paste-ready name + prompt (YAML: name, category, integrations)
  README.md    # what it does, when to use, connectors, first task
```

Then add one object to `bots.json`.

Categories: `productivity`, `marketing`, `sales`, `ops`, `personal`, `development`.

## PROFILE.md

YAML frontmatter (`name`, `category`, `integrations`) plus a paste-ready prompt: what the bot does, how it works, and the first task.

## README.md

What it does, when to use, connectors (same as the frontmatter), and one first task to send.

## Rules

- Unique one-line why in the README and in `bots.json`.
- Original profile. Do not paste botdirectory.ai prompts.
- Do not add Mustafa team bots (AI2sql, Stripe, Mixpanel, GSC, GA, Growth, X Draft, LinkedIn, App Store, Uptime, GitHub Bot, Reddit Search, X Search, Manager).
- No npm, Docker, OpenClaw, or SOUL.md install steps.

## PR

Fork, add the folder + `bots.json` entry, open a pull request.
