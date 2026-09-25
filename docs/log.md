# Learning log

## 2026-09-25 — Week 1, session 0 (setup)

**Did**

- Set up the repo: git init, .gitignore, .env, pushed empty commit
- Tried Gemini first — free tier is geo-blocked in Kosovo, switched to Groq
- Created a Groq key.
- Quickstart's model ID was dead (model_not_found) — had to query /models
- Sent a body with a GET to /models, got a 502 from Cloudflare, not a real API error
- Saved models.json; picked a model by checking supported_features for "tools"
- Ran a chat completion — accidentally used the safeguard variant, a classifier, not a general model
- Saved response.json
- Found Copilot had written my JSON annotations for me. Disabled it for the workspace

**Surprised me**

- reasoning_tokens are billed but never appear in content

**Don't understand yet**

- What the fourth finish_reason value is

**Next session starts with**

- Redo the field-guessing exercise properly, docs closed
