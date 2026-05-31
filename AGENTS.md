# Mood Closet Project Guide

## Project Overview

This repository contains a static single-page prototype for "Mood Closet", an interactive outfit board experience.

The app is currently built with plain HTML, CSS, and JavaScript in one file:

- `mood-closet.html` - main page and application logic
- `assets/` - local image assets used by the prototype

There is no build step, package manager, or framework configured yet.

## How To Run

Open `mood-closet.html` directly in a browser.

If a local server is needed, run one from the repository root, for example:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000/mood-closet.html
```

## Editing Guidelines

- Keep the project simple unless a framework is explicitly requested.
- Preserve the existing visual style and interaction model.
- Keep image paths relative to the repository root.
- Do not remove files from `assets/` unless they are clearly unused.
- Avoid unrelated refactors when making small visual or behavior changes.
- Prefer focused edits in `mood-closet.html`.

## Design Notes

- The page is a polished prototype, so layout, spacing, and visual details matter.
- Test changes on desktop and mobile widths when editing layout.
- Avoid text or controls overlapping at small screen sizes.
- Keep important UI visible in the first viewport.

## Git Workflow

Before finishing a task, check:

```bash
git status --short --branch
```

For user-facing changes, commit with a short message that explains the visible result.

The GitHub repository is:

```text
https://github.com/weishiyu072-sketch/vibe-fitting
```

