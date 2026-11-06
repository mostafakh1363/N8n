# PROJECT_CONTEXT

Short context for humans and coding agents working in this repository.
Secrets stay in local `.env` only — never commit tokens, passwords, or private keys.

## Purpose
CentralEstate Project Agent Instructions Project ID: `centralestate` Central skill registry: `mostafakh1363/ai-brain-skills` Before substantial work: 1. Apply shared rules from `global/AGENTS.md` in the central registry. 2. Read `registry/projects.yaml` and resolve the `centralestate` profile. 3. Expand its skill groups and direct skills, then load only task-relevant approved skills.

## Stack
see README

## Repository
- Local path: `/Users/mostafa/Documents/Codex/2026-09-06/new-chat/projects/N8n`
- Remote: `https://github.com/mostafakh1363/N8n.git`
- Current branch: `claude/persian-english-text-fix-5vjngs`

## Structure (top level)
```
.DS_Store
AGENTS.md
CLAUDE.md
docs/
```

## How to run / test / deploy
- See README for run/test/deploy steps.

## Integrations
- Telegram Bot API
- n8n automation
- Docker

## Current status
- Git status (summary): `## claude/persian-english-text-fix-5vjngs...origin/claude/persian-english-text-fix-5vjngs`
- Recent commits:
- 1099a73 Add central skill routing instructions for n8n
- 51466ef Add CLAUDE.md with Persian/English bidi text formatting rules

## Conventions
From AGENTS.md:
1. Apply shared rules from `global/AGENTS.md` in the central registry.
2. Read `registry/projects.yaml` and resolve the `centralestate` profile.
3. Expand its skill groups and direct skills, then load only task-relevant approved skills.

From CLAUDE.md:
## زبان و قوانین نگارش پاسخ فارسی
1. **شروع هر خط با کلمهٔ فارسی.** اولین کلمهٔ هر پاراگراف، هر جمله و هر مورد لیست باید فارسی باشد و هرگز نباید خط با کلمهٔ انگلیسی شروع شود. شمارهٔ لیست و علامت
2. **هر کلمه یا عبارت انگلیسی داخل بک‌تیک.** هر اصطلاح، نام ابزار، نام فایل یا مقدار انگلیسی که وسط جملهٔ فارسی می‌آید باید داخل بک‌تیک باشد، مثل `webhook` یا `
3. **عبارت چندکلمه‌ای انگلیسی را نشکن.** عبارت را یک‌تکه داخل یک بک‌تیک بگذار، مثل `pull request`؛ نه کلمه‌به‌کلمه در بک‌تیک‌های جدا.

## Open tasks / TODOs
- Review recent git commits and README for remaining work.

## Notes
- Do not commit `.env`, credentials, or signing secrets.
- Prefer small, reviewable changes aligned with AGENTS.md / README.
- Keep this file updated when purpose, stack, or major workflows change.
