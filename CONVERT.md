# Convert

You were just given this page. If you only have the URL, fetch it first:
https://raw.githubusercontent.com/mergisi/awesome-grokbot/main/CONVERT.md

Turn one OpenClaw or Hermes agent into one Grok Bot profile. Neutral. Do not clone OpenClaw or Hermes. Do not trash them. Memory and local files do not move. Write original text. Do not copy SOUL.md names, CTAs, or CrewClaw wording. Draft only. Do not send, post, pay, or contact anyone.

1. Do not ask them to type a source. If they already sent convert/openclaw.md or convert/hermes.md, use that pick and skip the widget.
   Otherwise show a Grok Bot question widget and stop. Wait for the tap.
   prompt: Convert from which source?
   allowCustom: false
   dismissOnMoveOn: true
   options:
   - OpenClaw
   - Hermes
   - I'm not sure
2. Ask them to attach or paste SOUL.md. Also take AGENTS.md, TOOLS.md, HEARTBEAT.md, or SKILL.md if they have them.
   If nothing is attached and nothing was pasted, say so and stop.
3. Map:
   - SOUL.md identity → Grok Bot Name + Description (PROFILE shape: what you do, how you work, first task, draft/research only).
   - AGENTS.md / TOOLS.md → Settings → Plugins list (only connectors Grok Bot actually has; if unknown, say browser login).
   - HEARTBEAT.md / cron → one routine idea. Do not create it until they say yes.
   - SKILL.md → tell them to record or paste as a skill after the bot exists.
4. Honest drop list (do not convert): MEMORY.md, USER.md, SQLite memory, local disk/gateway, any-model, Telegram/30 channels, self-hosted machine. Say: reconnect logins on Grok Bot's computer.
5. Output: proposed Name, PROFILE.md body, plugin list, first task. Offer to create the Grok Bot. Offer a PR into awesome-grokbot only if they ask.
6. Never more than one bot per convert unless they attach several SOUL files.
