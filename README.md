# Velrino's Skills

My collection of reusable skills for Codex. Each skill includes a `SKILL.md` with instructions for a specific kind of work.

## Skills

| Skill | What it does |
| --- | --- |
| [Copywriting Specialist](copywriting-specialist/SKILL.md) | Draft, review, and plan tests for direct-response copy across ads, emails, landing pages, social posts, messaging, video, and search content. |

## Install a skill

Clone this repository and copy the skill folder into your Codex skills directory.

```sh
git clone https://github.com/velrino/skills.git
mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
cp -Rn skills/copywriting-specialist "${CODEX_HOME:-$HOME/.codex}/skills/"
```

Open a new Codex session and invoke the skill by name.

```text
Use $copywriting-specialist to review this landing page for an English-speaking audience.
```
