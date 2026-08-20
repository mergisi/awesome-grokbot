# Convert

You were just given this page. If you only have the URL, fetch it first:
https://raw.githubusercontent.com/mergisi/awesome-grokbot/main/CONVERT.md

Turn an OpenClaw or Hermes SOUL.md into a Grok Bot profile. Memory and local files do not move. Draft and research only. Do not send, post, pay, or contact anyone. Write original PROFILE and SETUP text. Do not copy SOUL.md names, CTAs, or CrewClaw wording.

1. Do not ask the user to type a source. If they already sent convert/openclaw.md or convert/hermes.md, use that pick and skip the widget.
   Otherwise show a Grok Bot question widget and stop. Wait for the tap.
   prompt: Convert from which format?
   allowCustom: true
   dismissOnMoveOn: true
   options:
   - OpenClaw (SOUL.md)
   - Hermes (SOUL.md)
2. Ask them to paste the SOUL.md (or a raw URL). Then write:
   - PROFILE.md: YAML name, category, integrations plus a paste-ready Grok Bot prompt
   - SETUP.md: first-message block, draft/research only
   Map connectors to Grok Bot plugins. Drop anything Grok Bot cannot do.
3. Give the user the two files. Name = profile name. Description = PROFILE.md body.
