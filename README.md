# Awesome Grok Bot

Curated copy-paste profiles for Grok Bot.

[![Awesome List](https://img.shields.io/badge/awesome-list-blue.svg)](https://github.com/mergisi/awesome-grokbot)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: CC0](https://img.shields.io/badge/license-CC0-lightgrey.svg)](LICENSE)
[![Bots](https://img.shields.io/badge/bots-38-blueviolet.svg)](bots/)

## Quickstart

Grok Bot is an always-on teammate on a cloud computer. Official setup: [Get started](https://docs.x.ai/grok-bot/get-started) · download at [x.ai/bot](https://x.ai/bot) or [cursor.com/bot/onboarding](https://cursor.com/bot/onboarding) · [use cases](https://docs.x.ai/grok-bot/use-cases).

1. Open a bot folder and copy [SETUP.md](bots/productivity/daily-brief/SETUP.md) (example: Daily Brief).
2. Create a new Grok Bot and paste SETUP.md as the first message (or into Description if the bot already exists).
3. **Name** = the `name` / H1 in `PROFILE.md`. **Description** = the rest of `PROFILE.md`. Two fields.
4. Connect the plugins it names (**Settings → Plugins**), then send the First task from that bot's README.

## Plugins

From the official [skills and routines](https://docs.x.ai/grok-bot/skills-routines-and-automations) and [computer and apps](https://docs.x.ai/grok-bot/computer-and-apps) docs:

1. Open **Settings → Plugins**.
2. Add the connectors named in the profile's `integrations` (Gmail, Slack, GitHub, …).
3. Finish auth in the browser if asked.
4. Type `@` in the composer to attach a Bot, group, routine, or connector.
5. Type `/` to use a packaged or saved skill.
6. If a skill is missing from `/`, open **Settings → Plugins → Yours** and enable it for that Bot.
7. Then send the First task.

Prefer a connector when one exists. Use the cloud computer's browser when there is no plugin.

## Starter teams

Create both Bots, then put them in one thread.

- **Sales** — [Outbound Voice](bots/sales/outbound-voice/) + [Call Followup](bots/sales/call-followup/). Research and drafts go to one, the recap to the other.
- **Eng** — [Bug Reproduction](bots/development/bug-reproduction/) + [Issue Drafter](bots/development/issue-drafter/) + [PR Reviewer](bots/development/pr-reviewer/). Repro pack, then the issue, then the review.
- **Success** — [Account Health](bots/ops/account-health/) + [Support Replies](bots/ops/support-replies/). Watch list first, reply drafts second. Neither contacts a customer unless you send it.

## Contents

- [Productivity](#productivity)
- [Marketing](#marketing)
- [Sales](#sales)
- [Ops](#ops)
- [Personal](#personal)
- [Development](#development)

## Productivity

| Bot | Specialty | When to use | PROFILE.md |
| --- | --- | --- | --- |
| [Daily Brief](bots/productivity/daily-brief/) | morning briefing from calendar + inbox | one chat instead of five tabs before 9am | [PROFILE.md](bots/productivity/daily-brief/PROFILE.md) |
| [Inbox Triage](bots/productivity/inbox-triage/) | email triage and reply drafts | inbox zero without living in Gmail | [PROFILE.md](bots/productivity/inbox-triage/PROFILE.md) |
| [Meeting Notes](bots/productivity/meeting-notes/) | meeting summaries and action items | notes that already have owners and due dates | [PROFILE.md](bots/productivity/meeting-notes/PROFILE.md) |
| [Focus Defender](bots/productivity/focus-defender/) | protect deep-work blocks | meetings stop eating the only quiet hours | [PROFILE.md](bots/productivity/focus-defender/PROFILE.md) |
| [Slack Noise Filter](bots/productivity/slack-noise-filter/) | mute Slack noise, surface replies | the channel stays noisy; you only see what needs a reply | [PROFILE.md](bots/productivity/slack-noise-filter/PROFILE.md) |

## Marketing

| Bot | Specialty | When to use | PROFILE.md |
| --- | --- | --- | --- |
| [Social Queue](bots/marketing/social-queue/) | draft and queue social posts | one idea becomes a week of posts, not a blank composer | [PROFILE.md](bots/marketing/social-queue/PROFILE.md) |
| [SEO Pages](bots/marketing/seo-pages/) | titles, meta, internal links | pages on page two get a rewrite, not another blog idea | [PROFILE.md](bots/marketing/seo-pages/PROFILE.md) |
| [Competitor Watch](bots/marketing/competitor-watch/) | competitor site/pricing/changelog digest | you hear about their launch from the bot, not Twitter | [PROFILE.md](bots/marketing/competitor-watch/PROFILE.md) |
| [Newsletter Desk](bots/marketing/newsletter-desk/) | weekly newsletter from links + notes | the digest writes itself from what you already saved | [PROFILE.md](bots/marketing/newsletter-desk/PROFILE.md) |
| [Paid Media](bots/marketing/paid-media/) | campaign spend and realloc recommendations | the budget recommendation comes with numbers, not a live spend change | [PROFILE.md](bots/marketing/paid-media/PROFILE.md) |
| [Viral Tweet Scout](bots/marketing/viral-tweet-scout/) | high-engagement tweet craft | you steal the craft, not the post | [PROFILE.md](bots/marketing/viral-tweet-scout/PROFILE.md) |
| [Reddit Comment Finder](bots/marketing/reddit-comment-finder/) | relevant Reddit threads | the thread list is for reading, not drive-by comments | [PROFILE.md](bots/marketing/reddit-comment-finder/PROFILE.md) |

## Sales

| Bot | Specialty | When to use | PROFILE.md |
| --- | --- | --- | --- |
| [Meeting Prep](bots/sales/meeting-prep/) | pre-call brief | walk into the call already knowing the last promise | [PROFILE.md](bots/sales/meeting-prep/PROFILE.md) |
| [Call Followup](bots/sales/call-followup/) | draft follow-up emails after calls | the recap goes out while the call is still warm | [PROFILE.md](bots/sales/call-followup/PROFILE.md) |
| [Outbound Voice](bots/sales/outbound-voice/) | personalized outbound in the user's voice | volume without sounding like a sequence tool | [PROFILE.md](bots/sales/outbound-voice/PROFILE.md) |
| [Win Loss](bots/sales/win-loss/) | win/loss memos | lost deals become a pattern, not a feeling | [PROFILE.md](bots/sales/win-loss/PROFILE.md) |
| [Talent Scout](bots/sales/talent-scout/) | sourcing and outreach drafts | the shortlist has evidence, and nobody gets a message until you say so | [PROFILE.md](bots/sales/talent-scout/PROFILE.md) |
| [LinkedIn Signal Watch](bots/sales/linkedin-signal-watch/) | ICP signals on LinkedIn | the ICP signal is a watch list, not a LinkedIn message | [PROFILE.md](bots/sales/linkedin-signal-watch/PROFILE.md) |

## Ops

| Bot | Specialty | When to use | PROFILE.md |
| --- | --- | --- | --- |
| [Chief of Staff](bots/ops/chief-of-staff/) | daily ops digest | one front door instead of a status-meeting tax | [PROFILE.md](bots/ops/chief-of-staff/PROFILE.md) |
| [Support Replies](bots/ops/support-replies/) | draft support replies | first response in minutes, human still ships it | [PROFILE.md](bots/ops/support-replies/PROFILE.md) |
| [Vendor Inbox](bots/ops/vendor-inbox/) | invoices, renewals, vendor follow-ups | renewals stop surprising you on the card statement | [PROFILE.md](bots/ops/vendor-inbox/PROFILE.md) |
| [Security Questionnaire](bots/ops/security-questionnaire/) | draft security questionnaire answers | the 90-question form stops blocking the deal | [PROFILE.md](bots/ops/security-questionnaire/PROFILE.md) |
| [Expense Manager](bots/ops/expense-manager/) | weekly expense reconciliation | the weekly pile is a summary and drafts, not a sent chase | [PROFILE.md](bots/ops/expense-manager/PROFILE.md) |
| [Product Performance](bots/ops/product-performance/) | sourced performance investigations | the hotspot is a write-up with links, not a production toggle | [PROFILE.md](bots/ops/product-performance/PROFILE.md) |
| [Account Health](bots/ops/account-health/) | ranked customer watch list | the watch list is ranked evidence, not a customer email | [PROFILE.md](bots/ops/account-health/PROFILE.md) |
| [Feature Ask Finder](bots/ops/feature-ask-finder/) | repeated Slack feature asks | the same feature request stops living in 12 threads | [PROFILE.md](bots/ops/feature-ask-finder/PROFILE.md) |
| [What Did We Promise](bots/ops/what-did-we-promise/) | customer commitments | the promise is written down before the next call | [PROFILE.md](bots/ops/what-did-we-promise/PROFILE.md) |
| [QBR Pack Builder](bots/ops/qbr-pack-builder/) | QBR pack from notes | the QBR pack is a draft from notes, not a deck you send live | [PROFILE.md](bots/ops/qbr-pack-builder/PROFILE.md) |
| [New Hire Ramp](bots/ops/new-hire-ramp/) | first-week new-hire plan | week one has owners and calendar holds, not a wiki dump | [PROFILE.md](bots/ops/new-hire-ramp/PROFILE.md) |

## Personal

| Bot | Specialty | When to use | PROFILE.md |
| --- | --- | --- | --- |
| [Trip Concierge](bots/personal/trip-concierge/) | flights, hotels, itinerary sanity | the trip plan survives the 14-tab research spiral | [PROFILE.md](bots/personal/trip-concierge/PROFILE.md) |
| [Subscription Pruner](bots/personal/subscription-pruner/) | find unused subscriptions in mail | the $12/mo ghosts leave on purpose | [PROFILE.md](bots/personal/subscription-pruner/PROFILE.md) |
| [Household Ops](bots/personal/household-ops/) | shared calendar, chores, errands | the family chat stops being the project manager | [PROFILE.md](bots/personal/household-ops/PROFILE.md) |
| [Reading Digest](bots/personal/reading-digest/) | weekly article pack | the reading list actually gets read | [PROFILE.md](bots/personal/reading-digest/PROFILE.md) |

## Development

| Bot | Specialty | When to use | PROFILE.md |
| --- | --- | --- | --- |
| [PR Reviewer](bots/development/pr-reviewer/) | PR risk/tests/context review | review starts with the scary diff, not the title | [PROFILE.md](bots/development/pr-reviewer/PROFILE.md) |
| [Changelog Bot](bots/development/changelog-bot/) | release notes from merged PRs | ship notes without a Friday archaeology session | [PROFILE.md](bots/development/changelog-bot/PROFILE.md) |
| [Issue Drafter](bots/development/issue-drafter/) | Slack/thread to GitHub issue | the bug is written down before it evaporates | [PROFILE.md](bots/development/issue-drafter/PROFILE.md) |
| [Docs Writer](bots/development/docs-writer/) | README / API docs from the repo | docs catch up to the code in one pass | [PROFILE.md](bots/development/docs-writer/PROFILE.md) |
| [Bug Reproduction](bots/development/bug-reproduction/) | staging repro packs | the ticket gets a repro pack, not a guess in the comments | [PROFILE.md](bots/development/bug-reproduction/PROFILE.md) |

## Submit your bot

Add `bots/[category]/[slug]/{PROFILE.md,SETUP.md,README.md}`, add a `bots.json` entry, open a PR. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Related

- [Grok Bot](https://x.ai/bot)
- [Use cases](https://docs.x.ai/grok-bot/use-cases)

## License

[CC0 1.0 Universal](LICENSE) — public domain. Copy a profile, ship a bot.
