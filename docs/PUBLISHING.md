# Publishing Guide

Use this guide to publish the project as a clean GitHub repository.

## Recommended Repository Name

```text
x-algorithm-content-strategist
```

## Before Publishing

Confirm that the repository root is this folder:

```text
x-algorithm-content-strategist/
```

Do not publish the parent workspace if it contains unrelated projects or private files.

## First-Time Git Setup

From inside `x-algorithm-content-strategist/`:

```bash
git init
git add .
git commit -m "Initial public release"
git branch -M main
```

Create a new GitHub repository, then connect it:

```bash
git remote add origin https://github.com/<your-username>/x-algorithm-content-strategist.git
git push -u origin main
```

## Repository Settings

After pushing to GitHub:

1. Add a short repository description:
   `Codex skill for X/Twitter-style content strategy, scoring, and revision.`
2. Add topics:
   `codex-skill`, `content-strategy`, `twitter`, `x`, `recommendation-systems`, `social-media`, `ai-agents`
3. Enable Issues.
4. Enable Discussions if you want community examples and feedback.
5. Check that GitHub Actions is enabled.
6. Confirm the MIT license is detected by GitHub.

## Suggested Release

Create release:

```text
v0.1.0
```

Release title:

```text
Initial public release
```

Release notes:

```text
Initial release of x-algorithm-content-strategist, a Codex skill for turning X/Twitter-style recommendation logic into executable content strategy.

Includes:
- skill workflow
- scoring rubric
- real-photo-first image guidance
- GitHub contribution templates
- validation workflow
```
