# local-web-design-skill

Public Cursor skill for **local business marketing websites** (Next.js landing pages).

**Source of truth:** this repo (`emist3r/local-web-design-skill`).  
Also used inside the private Studyabroad studio (vendored copy).

Pairs with [EMIST3R/skills](https://github.com/EMIST3R/skills) (`emil-design-eng`, `mobile-native`, etc.).

## Install into a project

```bash
mkdir -p .cursor/skills
git clone --depth 1 https://github.com/emist3r/local-web-design-skill.git /tmp/lwds
cp -R /tmp/lwds/.cursor/skills/local-web-design .cursor/skills/
```

Or personal (all projects):

```bash
mkdir -p ~/.cursor/skills
cp -R /tmp/lwds/.cursor/skills/local-web-design ~/.cursor/skills/
```

## What it enforces

- Brand-first, full-bleed hero; tight first-viewport budget
- No hero cards / overlay badges
- Expressive fonts; theme CSS variables; avoid AI-default purple/cream-terracotta looks
- Local images (not Facebook CDN alone)
- LINE CTA + QR when present; Maps via resolved place URL / formatted address
- 2–3 intentional motions (with `emil-design-eng`)

## Skill path

[`.cursor/skills/local-web-design/SKILL.md`](.cursor/skills/local-web-design/SKILL.md)
