# local-web-design-skill

Public Cursor skill for **local business marketing websites** (Next.js landing pages).

## Where it lives publicly

**Primary (live now):**  
https://github.com/EMIST3R/skills/tree/main/skills/local-web-design

```bash
npx skills@latest add EMIST3R/skills
```

This folder is the same skill packaged as a dedicated repo (`emist3r/local-web-design-skill`) for one-skill installs.

## Install only this skill into a project

```bash
mkdir -p .cursor/skills
git clone --depth 1 https://github.com/EMIST3R/skills.git /tmp/emist3r-skills
cp -R /tmp/emist3r-skills/skills/local-web-design .cursor/skills/
```

Or clone this dedicated repo once it exists on GitHub, then:

```bash
cp -R .cursor/skills/local-web-design /path/to/project/.cursor/skills/
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
