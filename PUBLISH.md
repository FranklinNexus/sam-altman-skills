# Publish Checklist

Suggested repository name: `sam-altman-skills`

Suggested description:

```text
Portable Sam Altman-inspired ambition, compounding, focus, growth, and AI strategy skill package for Cursor, Claude Code, Antigravity, and AGENTS.md-compatible agents.
```

## Before Creating The Remote

Run:

```powershell
python .\scripts\validate.py
git status --short
```

Expected result:

- Validation passes.
- `git status --short` is empty.

## Create The GitHub Repository

Create an empty GitHub repository named `sam-altman-skills`.

Do not initialize it with a README, license, or `.gitignore`; this repository already contains those files where needed.

## Push

Use HTTPS:

```powershell
git remote add origin https://github.com/<your-github-user>/sam-altman-skills.git
git branch -M main
git push -u origin main
```

Or use SSH:

```powershell
git remote add origin git@github.com:<your-github-user>/sam-altman-skills.git
git branch -M main
git push -u origin main
```

## After Push

Open the GitHub repository page and confirm these paths are visible:

- `skills/sam-altman/SKILL.md`
- `skills/sam-altman/PLAYBOOK.md`
- `.agents/skills/sam-altman.md`
- `scripts/install.ps1`
- `scripts/validate.py`
