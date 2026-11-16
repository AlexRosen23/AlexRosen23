# AlexRosen23 (GitHub profile): features

This is the special GitHub repository whose `README.md` is shown on the owner's GitHub profile page. It has one
file of content: a profile README that introduces the owner, gives a few headline numbers, and links to about 40
projects grouped into seven categories. It is for visitors, such as recruiters and collaborators, who want a quick
map of what the owner has built.

**This is the source-of-truth features list.** Every PR that adds, changes, removes or switches off something a person
can see or use updates this file in the same PR (see "Keeping this file true").

- **Repo:** AlexRosen23/AlexRosen23 (public) · **Folder:** none (no local folder; edited through fresh clones)
- **Status:** Live (shown on the GitHub profile) · **Version:** none · **`main`:** `10e3293` (2026-11-15)
- **Last updated:** 2026-11-15, written from the README, git history and merged-PR list.

**Status words** (a feature with no status word is live):
| Word | Means |
| --- | --- |
| *Live* | on `main` and shown on the profile |

## At a glance
| | |
| --- | --- |
| Content | 1 file (`README.md`, 145 lines), no code, no build step |
| Sections | 6 top-level headings; the project directory has 7 category tables |
| Projects linked | 40 rows across the 7 category tables, plus 9 "selected projects" and 1 flagship |
| Public projects named as public | 4 (language-model lab, retrieval workbench, MLOps lab, engineering case studies) |
| Merged PRs | 1 (PR #1, 2026-11-10) |
| Commits on `main` | 3 |
| Tests / CI | none; no workflow files |

## Contents
1. What it is and who it's for
2. How to run it
3. Architecture at a glance
4. Features
5. Integrations
6. Data and privacy
7. Tests and evidence
8. Known limits and gaps
9. Change log

## 1. What it is and who it's for

- A profile README. GitHub shows it at the top of github.com/AlexRosen23 because the repo name matches the username.
- Audience: people who land on the profile and want to know who the owner is and what the work looks like.
- It is a directory, not a product. Each project it lists has its own repository and README.

## 2. How to run it

There is nothing to run or install.

- **Read it:** open github.com/AlexRosen23, or open `README.md` in this repo.
- **Change it:** edit `README.md` on a branch and open a PR. GitHub re-renders the profile when `main` changes.
- **Environment variables, ports, launch config:** none.

## 3. Architecture at a glance

```
README.md      the profile page (Markdown with HTML-free tables and links)
FEATURES.md    this file
```

No data flow. Every link points to another GitHub repository or to LinkedIn.

## 4. Features

### Introduction
- **Headline and tagline**: one line of focus areas (AI systems, full-stack software, autonomous agents, interactive 3D). `README.md`
- **Role and links**: current role, school, city, and links to LinkedIn and the portfolio repository. `README.md`
- **Summary paragraph**: says the owner builds software that connects AI, automation, simulation and interactive experiences. `README.md`
- **AI-assistance statement**: says plainly that the owner sets direction, requirements and architecture, reviews changes, runs evaluations and decides what ships, and that Claude Code writes much of the implementation. `README.md`

### By the numbers
- **Activity table**: about 40 projects, about 2,700 git commits, about 177 hours of measured Claude Code session time, and an illustrative 1,000 to 3,000 hours of conventional-development effort. `README.md`
- **Caveat note**: says the first three numbers are counts, the last is a rough estimate (25 to 75 hours per project), it is not measured time saved, and the 177 hours cover Claude Code sessions only. `README.md`
- **Private-repositories note**: explains that many projects are private, that their READMEs describe purpose, stack, setup and activity, and names the four public ones with links. `README.md`

### Flagship and selected projects
- **Flagship section**: one project described with its stack and repository activity (commit, merged-PR, unit/integration test-file and end-to-end spec counts as of the 2026-11-10 refresh). `README.md`
- **Selected projects table**: 9 projects with focus, public or not, and a one-line description. `README.md`

### Project directory
- **Seven category tables** (40 rows in total): AI agents and command centers (6), AI engineering and ML systems (4), generative maker tools (9), 3D / simulation / forecasting (6), games and interactive worlds (4), data / research / markets (7), products and personal projects (4). `README.md`
- **Honest labels**: trading and betting projects are marked as paper-only, simulated or record-keeping, and the profile says no live trading is claimed. `README.md`

### How I work
- **Four working principles**: AI-assisted and human-directed; branch-based development with gitleaks secret scanning before pushes; evidence over demos (live vs synthetic data, measured vs estimated); reproducibility (setup documented, Claude Code usage measured from session transcripts, cache reads reported separately). `README.md`
- **Tools list**: one line of languages and tools. `README.md`

## 5. Integrations

- Links to LinkedIn, the owner's other GitHub repositories, and the Claude Code site.
- No API calls, no automation, no GitHub Actions.

## 6. Data and privacy

- Stores nothing but the Markdown file.
- Contains only information the owner chose to make public: name, employer, school, city, LinkedIn link.
- No secrets, tokens, emails or customer data. Private projects are named and described in one line; their contents are not published.

## 7. Tests and evidence

- No automated tests and no CI (no workflow files). Counted from source on 2026-11-15, not run.
- The numbers in "By the numbers" and the flagship stats are the owner's own counts from the 2026-11-10 refresh (PR #1). This file does not re-check them.
- Link health has not been checked automatically. Unverified.

## 8. Known limits and gaps

- The numbers are a snapshot and go stale as the owner commits. Only the 2026-11-10 refresh updated them.
- The README uses an emoji in its greeting.
- No automated link checker, so a renamed or deleted repo would leave a dead link until someone notices.
- The directory rows are one-line descriptions; some projects may be further along or more changed than the line says.

## 9. Change log

| Date | PR | Change |
| --- | --- | --- |
| 2026-11-10 | #1 | Added the public AI/ML projects and refreshed the flagship's statistics (audit 2026-11-10). |
| 2026-11-07 | none (direct commits `edd7c80`, `0dd4e3e`) | Profile README with every project and a one-line description, then a small edit. |

## Keeping this file true

- **Same PR, same change:** a PR that adds, changes or removes a section or project row in `README.md` updates this file too.
- **Status moves with reality:** when a project changes from private to public (or the reverse), fix the labels in `README.md` and the counts here.
- **Only what is true:** the counts at the top of this file are re-counted from `README.md` when it changes.
- **Public repo rule:** this file is public. No private details, no secrets, no machine paths.
