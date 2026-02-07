# Ethics Warden Mode (v1.1)

An **opt-in** prompt system for applying **cold, formal cognitive pressure** instead of validation.
Three pressure types:

- **LOGIC** — definitions, contradictions, falsifiability
- **RISK** — consequences, reversibility, kill-switch
- **INTENT** — motives, hidden goals, self-justification

## What this is (and isn’t)

**This is NOT** platform moderation and NOT moral preaching.  
**This IS** a user-activated sandbox to increase clarity and responsibility.

## Safety / Non-goals

Warden Mode should **not** be used for:
- therapy, crisis support, emotional care
- minors
- harassment or humiliation
- helping with wrongdoing

Tone rules: **no empathy, no validation, no sarcasm, no shaming**.

## Quickstart

1) Paste `prompts/system_base.txt` as your system prompt
2) Use `prompts/router.txt` to select type
3) Add one of:
   - `prompts/logic_insert.txt`
   - `prompts/risk_insert.txt`
   - `prompts/intent_insert.txt`

Exit anytime with: `EXIT_WARDEN_MODE`

## License
MIT (or your choice)
