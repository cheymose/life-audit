# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A single-file Life Audit web app (`index.html`) — no build system, no dependencies, no package manager. Open the file directly in a browser to use.

The app guides users through a structured audit of key life areas, helps them reflect on their current state, and lets them create a focused action plan for areas they want to improve.

## Architecture

Everything lives in `index.html`: inline CSS in `<style>`, markup in `<body>`, and vanilla JS in a `<script>` block at the bottom.

## Workflow

```bash
# View the app
open index.html

# Push changes
git add index.html
git commit -m "Your message"
git push
```

Remote: https://github.com/cheymose/life-audit

## Git Discipline

Commit and push to GitHub after every meaningful change — do not batch up multiple unrelated changes into one commit.

- Commit messages should use imperative mood and describe *what* changed
- Push immediately after each commit: `git push`
- Never leave uncommitted changes at the end of a work session
