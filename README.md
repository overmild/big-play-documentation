# Big Play

> One-line pitch: _[Replace with a single sentence describing what Big Play is and who it's for.]_

**Status:** 🌱 Early stage — documentation & planning only, no code yet.

This repository is currently a **documentation-only** hub. Before we write a line of code, we're using it to line up *why* we're building this, *what* we're building, and *how* we'll work together — since the team spans different technical backgrounds.

If you're new here, start with the section below that matches you.

## Where to start, by role

| You are... | Start here |
|---|---|
| Curious / non-technical, want the big picture | [`docs/00-overview/vision.md`](docs/00-overview/vision.md) |
| A contributor with an idea | [`docs/02-ideation`](docs/02-ideation) |
| A contributor wanting to help write requirements | [`docs/01-requirements`](docs/01-requirements) |
| Someone about to open a PR or edit a file | [`CONTRIBUTING.md`](CONTRIBUTING.md) |
| A maintainer / decision-maker | [`GOVERNANCE.md`](GOVERNANCE.md) |

## Repo map

```
big-play/
├── README.md                 ← you are here
├── CONTRIBUTING.md           ← how to contribute, at any skill level
├── CODE_OF_CONDUCT.md        ← how we treat each other
├── GOVERNANCE.md             ← who decides what, and how
├── docs/
│   ├── 00-overview/          ← vision, goals, glossary — "why"
│   ├── 01-requirements/      ← what the product must do
│   ├── 02-ideation/          ← lightweight proposals / RFCs for new ideas
│   ├── 03-decisions/         ← ADRs — decisions once they're made, and why
│   ├── 04-roadmap/           ← what's next, in what order
│   └── 05-meeting-notes/     ← running log of syncs & decisions made live
└── .github/                  ← issue & PR templates
```

## The lifecycle an idea follows here

```
 idea → docs/02-ideation (proposal)
          │
          ▼ discussed, refined, accepted
 docs/01-requirements (formal requirement)
          │
          ▼ big/structural choices get recorded
 docs/03-decisions (ADR)
          │
          ▼ scheduled
 docs/04-roadmap
```

Not every idea needs every step — see [`docs/02-ideation/README.md`](docs/02-ideation/README.md) for when to use what.

## Reusing this template for a different project

Everything under `docs/`, plus `CONTRIBUTING.md` and `GOVERNANCE.md`, is written to be project-agnostic. To reuse this for a new project: copy the repo, replace the contents of `docs/00-overview/vision.md`, clear out anything under `docs/01-requirements`, `docs/02-ideation`, `docs/03-decisions`, and `docs/04-roadmap` except the templates and `README.md` index files, and update the name at the top of this file.
