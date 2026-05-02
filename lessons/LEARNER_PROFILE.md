# Learner Profile — Adam

This file is maintained by Claude and updated after every lesson. It provides ongoing context about who Adam is, his current proficiency level, and what has been covered so far — so any new session can pick up exactly where we left off.

---

## Who He Is

- **Seasoned entrepreneur** who has run and scaled businesses.
- Has **spearheaded software projects** and worked closely with development teams — understands product strategy, user experience, and how to direct engineers.
- Now learning to **build himself**, both frontend and backend.
- Primary drive is the **end product and user experience**, not the code for its own sake.
- Learns well through **practical, hands-on examples** with real context — not abstract theory.
- Prefers **clear mental models** over technical jargon. Once the model clicks, he moves fast.

---

## Current Knowledge Level

| Area | Level |
|---|---|
| Product thinking / UX | Advanced |
| Working with dev teams | Advanced |
| Git & GitHub concepts | Beginner → building foundations |
| HTML / CSS / JS | Beginner (has seen the code, needs more reps) |
| Backend / databases | Not yet started |
| Terminal / command line | Early exposure |

---

## Lessons Completed

### Lesson 01 — Git & GitHub for New Developers
**Date:** May 2026
**File:** `lesson-01-git-and-github.pdf`

**What was covered:**
- Git vs GitHub — the core distinction and mental model
- Version control — commits as snapshots, the 3-step workflow
- Push and pull — syncing between local and cloud
- File recovery — `git restore` vs `git pull`, and when to use each
- Branching — parallel timelines, production vs dev branch strategy
- Pull requests — the professional merge workflow
- Cloning vs forking — getting any repo running locally
- Folder path misconceptions — why relative paths mean location rarely matters

**Hands-on project built:**
- Tic Tac Toe web game (`tictactoe.html`) — HTML, CSS, vanilla JS
- GitHub repo initialized and configured: `github.com/AdamVisutag/ClaudeTut`
- Live demonstration of: file deletion + recovery, branching, feature development on `dev`, pushing to GitHub

**Key things that clicked fast:**
- The production/dev branch analogy (he arrived at it himself before being told)
- Git as a save system, GitHub as cloud backup
- Surgical nature of `git pull` (not a wipe and reinstall)

---

### Lesson 02 — Building a Real Project from Scratch
**Date:** May 2026
**File:** `lesson-02-building-a-real-project.html`

**What was covered:**
- Fork vs clone — ownership model, when to use each, the "fully independent copy" method
- Multi-project Claude sessions — open Claude inside the target project folder for correct context
- CLAUDE.md — the product brain, auto-loaded every session, permanent instruction card
- DEV_CONTEXT.md — technical brain for VS Code sessions: tech stack, current state, what's next
- Providing files as context — dropping PDFs and images into the project folder for Claude to read
- Starting a new Git repo from scratch — `git init` → remote → context files → first commit → push
- .gitignore — what to exclude (`.claude/`, `node_modules/`, `.env`, `.next/`)
- Frontend tech stack planning — Next.js 15, TypeScript, Tailwind CSS, shadcn/ui, Three.js + GaussianSplats3D, Zustand, TanStack Query
- Responsive layout architecture — desktop 3-panel vs mobile stacked, Tailwind breakpoints
- Node.js v24.15.0 installed via `winget`
- Next.js 15.5.15 scaffolded (TypeScript, Tailwind v4, ESLint, App Router, Turbopack)
- npm naming rules — lowercase only, no capitals

**Hands-on project built:**
- Recon Volumetrics GitHub repo created and first commit pushed
- Planning PDFs and UX mockup added to `Planning Files/`
- CLAUDE.md and DEV_CONTEXT.md written for the project
- Next.js 15 app scaffolded and running at `localhost:3000`

**Key things that clicked fast:**
- "CLAUDE.md is the instruction card the project carries with it forever"
- Immediately grasped why fork = ownership and clone = access
- Connected the three-layer product structure (service / platform / infrastructure) clearly

---

## Current Knowledge Level

| Area | Level |
|---|---|
| Product thinking / UX | Advanced |
| Working with dev teams | Advanced |
| Git & GitHub concepts | Building foundations — commits, push/pull, branches, remotes, .gitignore |
| HTML / CSS / JS | Beginner (has seen the code, needs more reps) |
| Frontend frameworks | Early exposure — Next.js scaffolded, concepts introduced |
| Terminal / command line | Growing — ran winget, npm, npx, git commands independently |
| Backend / databases | Not yet started |

---

## Notes for Future Sessions

- Start with the "why" and the mental model before showing commands — he connects to purpose first.
- He responds well to analogies from business (deployment = release, branch = parallel workstream).
- Lessons should be saved **locally only** — never push the `lessons/` folder to GitHub.
- After each lesson, update this file with what was covered and current level.
- Next natural step for Recon Volumetrics: **install shadcn/ui → build layout shell → 3D viewer**.
- Next natural step for learning: **React fundamentals** — components, props, state, how JSX works.
