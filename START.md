# Start

One page for a blank Grok Bot. Paste it, then say the job. The bot picks 2–4 profiles from this list and builds a small team.

Raw URL (so a bot can fetch this page): https://raw.githubusercontent.com/mergisi/awesome-grokbot/main/START.md

## Bootstrap

Copy everything in this block into a new Grok Bot, then send your goal.

```
You are standing up a small Grok Bot team from this page. Draft and research only. Do not send, post, pay, or contact anyone.

1. Ask one sentence: what job should this team own?
2. If the goal is unclear, ask one clarifying question. Do not dump this catalog.
3. Pick 2–4 bots from the Index below. Never more than 4. Prefer a starter team when it fits:
   - Sales: Outbound Voice + Call Followup
   - Eng: Bug Reproduction + Issue Drafter + PR Reviewer
   - Success: Account Health + Support Replies
4. Create each picked Grok Bot. Name = the profile name. Description = that bot's PROFILE.md body. Fetch the body from https://raw.githubusercontent.com/mergisi/awesome-grokbot/main/<folder>/PROFILE.md — do not invent the prompt.
5. Tell the user which Settings → Plugins to connect once (the union of the picked bots).
6. Put the new bots in one thread or group. Give the first task for the lead bot (from that bot's README).
```

## Index

Name | one-line why | category | plugins | folder. 56 bots. No profile text here.

| Name | Why | Category | Plugins | Folder |
| --- | --- | --- | --- | --- |
| Daily Brief | one chat instead of five tabs before 9am | productivity | Google Calendar, Gmail, Slack | [bots/productivity/daily-brief/](bots/productivity/daily-brief/) |
| Inbox Triage | inbox zero without living in Gmail | productivity | Gmail | [bots/productivity/inbox-triage/](bots/productivity/inbox-triage/) |
| Meeting Notes | notes that already have owners and due dates | productivity | Google Docs, Slack | [bots/productivity/meeting-notes/](bots/productivity/meeting-notes/) |
| Focus Defender | meetings stop eating the only quiet hours | productivity | Google Calendar, Slack | [bots/productivity/focus-defender/](bots/productivity/focus-defender/) |
| Slack Noise Filter | the channel stays noisy; you only see what needs a reply | productivity | Slack | [bots/productivity/slack-noise-filter/](bots/productivity/slack-noise-filter/) |
| Bot Team Coach | name the jobs, pick the plugins, keep the roster small | productivity | — | [bots/productivity/bot-team-coach/](bots/productivity/bot-team-coach/) |
| One to One Brief | walk into the 1:1 already knowing last time and today's ask | productivity | Google Calendar, Slack | [bots/productivity/one-to-one-brief/](bots/productivity/one-to-one-brief/) |
| Standup Desk | the standup is a collected note, not a channel post | productivity | Slack | [bots/productivity/standup-desk/](bots/productivity/standup-desk/) |
| Social Queue | one idea becomes a week of posts, not a blank composer | marketing | Notion, X, LinkedIn | [bots/marketing/social-queue/](bots/marketing/social-queue/) |
| SEO Pages | pages on page two get a rewrite, not another blog idea | marketing | Google Search Console, GitHub | [bots/marketing/seo-pages/](bots/marketing/seo-pages/) |
| Competitor Watch | you hear about their launch from the bot, not Twitter | marketing | Slack | [bots/marketing/competitor-watch/](bots/marketing/competitor-watch/) |
| Newsletter Desk | the digest writes itself from what you already saved | marketing | Gmail, Google Docs | [bots/marketing/newsletter-desk/](bots/marketing/newsletter-desk/) |
| Paid Media | the budget recommendation comes with numbers, not a live spend change | marketing | Slack, Google Drive | [bots/marketing/paid-media/](bots/marketing/paid-media/) |
| Viral Tweet Scout | you steal the craft, not the post | marketing | X | [bots/marketing/viral-tweet-scout/](bots/marketing/viral-tweet-scout/) |
| Reddit Comment Finder | the thread list is for reading, not drive-by comments | marketing | Reddit | [bots/marketing/reddit-comment-finder/](bots/marketing/reddit-comment-finder/) |
| Profile Review | the LinkedIn audit is suggested edits, not a live profile change | marketing | LinkedIn | [bots/marketing/profile-review/](bots/marketing/profile-review/) |
| Brand Watch | the mention digest is for reading, not a reply thread | marketing | Slack, X | [bots/marketing/brand-watch/](bots/marketing/brand-watch/) |
| Content Remix | one draft becomes variants, none of them go live | marketing | Notion | [bots/marketing/content-remix/](bots/marketing/content-remix/) |
| Meeting Prep | walk into the call already knowing the last promise | sales | Gmail, Google Calendar, Slack | [bots/sales/meeting-prep/](bots/sales/meeting-prep/) |
| Call Followup | the recap goes out while the call is still warm | sales | Gmail, Google Calendar | [bots/sales/call-followup/](bots/sales/call-followup/) |
| Outbound Voice | volume without sounding like a sequence tool | sales | Gmail, LinkedIn | [bots/sales/outbound-voice/](bots/sales/outbound-voice/) |
| Win Loss | lost deals become a pattern, not a feeling | sales | Notion, Slack | [bots/sales/win-loss/](bots/sales/win-loss/) |
| Talent Scout | the shortlist has evidence, and nobody gets a message until you say so | sales | Gmail, Google Calendar, LinkedIn | [bots/sales/talent-scout/](bots/sales/talent-scout/) |
| LinkedIn Signal Watch | the ICP signal is a watch list, not a LinkedIn message | sales | LinkedIn | [bots/sales/linkedin-signal-watch/](bots/sales/linkedin-signal-watch/) |
| Contact CRM | the follow-up list is a list, not an outbound send | sales | Gmail, Google Calendar | [bots/sales/contact-crm/](bots/sales/contact-crm/) |
| Proposal Desk | the proposal stays a draft until you send it | sales | Google Docs, Slack | [bots/sales/proposal-desk/](bots/sales/proposal-desk/) |
| Chief of Staff | one front door instead of a status-meeting tax | ops | Slack, Google Calendar, Notion | [bots/ops/chief-of-staff/](bots/ops/chief-of-staff/) |
| Support Replies | first response in minutes, human still ships it | ops | Gmail, Notion | [bots/ops/support-replies/](bots/ops/support-replies/) |
| Vendor Inbox | renewals stop surprising you on the card statement | ops | Gmail, Google Drive | [bots/ops/vendor-inbox/](bots/ops/vendor-inbox/) |
| Security Questionnaire | the 90-question form stops blocking the deal | ops | Google Drive, Notion | [bots/ops/security-questionnaire/](bots/ops/security-questionnaire/) |
| Expense Manager | the weekly pile is a summary and drafts, not a sent chase | ops | Gmail, Google Drive | [bots/ops/expense-manager/](bots/ops/expense-manager/) |
| Product Performance | the hotspot is a write-up with links, not a production toggle | ops | GitHub, Slack | [bots/ops/product-performance/](bots/ops/product-performance/) |
| Account Health | the watch list is ranked evidence, not a customer email | ops | Slack, Notion, Gmail | [bots/ops/account-health/](bots/ops/account-health/) |
| Feature Ask Finder | the same feature request stops living in 12 threads | ops | Slack | [bots/ops/feature-ask-finder/](bots/ops/feature-ask-finder/) |
| What Did We Promise | the promise is written down before the next call | ops | Slack, Google Drive | [bots/ops/what-did-we-promise/](bots/ops/what-did-we-promise/) |
| QBR Pack Builder | the QBR pack is a draft from notes, not a deck you send live | ops | Slack, Google Drive | [bots/ops/qbr-pack-builder/](bots/ops/qbr-pack-builder/) |
| New Hire Ramp | week one has owners and calendar holds, not a wiki dump | ops | Google Calendar, Slack | [bots/ops/new-hire-ramp/](bots/ops/new-hire-ramp/) |
| Account Desk | one account, one chat, no customer email until you send it | ops | Slack, Gmail | [bots/ops/account-desk/](bots/ops/account-desk/) |
| SaaS Finance | the weekly money read is a memo, not a refund or a dunning send | ops | Stripe, Gmail | [bots/ops/saas-finance/](bots/ops/saas-finance/) |
| Churn Watch | the at-risk list is ranked evidence, not a save-the-account email | ops | Slack, Notion, Gmail | [bots/ops/churn-watch/](bots/ops/churn-watch/) |
| Resume Screen | the score is a shortlist, not a candidate email | ops | Gmail, Google Drive | [bots/ops/resume-screen/](bots/ops/resume-screen/) |
| Cloud Spend | the bill note is a recommendation, not an account change | ops | Gmail, Google Drive | [bots/ops/cloud-spend/](bots/ops/cloud-spend/) |
| Incident Desk | the timeline is a write-up, not a production toggle | ops | Slack, GitHub | [bots/ops/incident-desk/](bots/ops/incident-desk/) |
| Trip Concierge | the trip plan survives the 14-tab research spiral | personal | Gmail, Google Calendar | [bots/personal/trip-concierge/](bots/personal/trip-concierge/) |
| Subscription Pruner | the $12/mo ghosts leave on purpose | personal | Gmail | [bots/personal/subscription-pruner/](bots/personal/subscription-pruner/) |
| Household Ops | the family chat stops being the project manager | personal | Google Calendar, Slack | [bots/personal/household-ops/](bots/personal/household-ops/) |
| Reading Digest | the reading list actually gets read | personal | Notion | [bots/personal/reading-digest/](bots/personal/reading-digest/) |
| Charge Dispute Draft | the dispute letter stays a draft until you submit it | personal | Gmail | [bots/personal/charge-dispute-draft/](bots/personal/charge-dispute-draft/) |
| PR Reviewer | review starts with the scary diff, not the title | development | GitHub | [bots/development/pr-reviewer/](bots/development/pr-reviewer/) |
| Changelog Bot | ship notes without a Friday archaeology session | development | GitHub | [bots/development/changelog-bot/](bots/development/changelog-bot/) |
| Issue Drafter | the bug is written down before it evaporates | development | GitHub, Slack | [bots/development/issue-drafter/](bots/development/issue-drafter/) |
| Docs Writer | docs catch up to the code in one pass | development | GitHub | [bots/development/docs-writer/](bots/development/docs-writer/) |
| Bug Reproduction | the ticket gets a repro pack, not a guess in the comments | development | GitHub, Slack | [bots/development/bug-reproduction/](bots/development/bug-reproduction/) |
| Repo Hardener | the hygiene review is issues and PRs, not a push to main | development | GitHub | [bots/development/repo-hardener/](bots/development/repo-hardener/) |
| Deploy Watch | the status board is a read, not a merge or a ship | development | GitHub, Slack | [bots/development/deploy-watch/](bots/development/deploy-watch/) |
| Query Helper | the SQL stays a draft, never a write against a live database | development | GitHub | [bots/development/query-helper/](bots/development/query-helper/) |
