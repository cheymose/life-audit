# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A single-file Life Audit web app (`index.html`) — no build system, no dependencies, no package manager. Open the file directly in a browser to use.

The app guides users through a structured audit of key life areas, helps them reflect on their current state, and lets them create a focused action plan for areas they want to improve.

The full question set is defined in the PDF: `/Users/chey/Downloads/LIFE AUDIT — FULL QUESTION SET (FINAL STRUCTURE).pdf`

### Section Structure (26 sections, ~200 questions)

1. Current State Snapshot (9 questions)
2. Why Are You Here? (8 questions)
3. Identity Compression (9 questions)
4. The Identity Gap (8 questions)
5. Positive Traits, Negative Traits & Origins (9 questions)
6. Fear Mapping (8 questions)
7. Anxiety & Trigger Awareness (8 questions)
8. Internal Threat Assessment (8 questions)
9. Mental Tabs Audit (8 questions)
10. Physical Health & Energy (8 questions)
11. Routine, Discipline & Delivery (8 questions)
12. Financial & Structural Reality (8 questions)
13. Social & Environment Architecture (8 questions)
14. Relationship Audit (8 questions)
15. Communication Audit (8 questions)
16. Personal Operating Limits / Boundaries (8 questions)
17. Online You vs Real World You (8 questions)
18. Connectivity Off-Switch (8 questions)
19. Ambition, Purpose & Potential (8 questions)
20. Values & Non-Negotiables (8 questions)
21. Mirror Report / Brutal Honesty (8 questions)
22. Category Scoring — rate 11 life areas 1–10 (Identity, Emotional stability, Physical health, Mental clarity, Discipline, Relationships, Communication, Boundaries, Screen-life balance, Purpose and direction, Integrity)
23. Pattern Recognition (6 questions)
24. Priority Repair List (6 questions)
25. The 30-Day Reset Plan (6 questions)
26. Final Commitment (4 questions)

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
