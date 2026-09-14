# Contributing to Big Play

Everyone's contribution matters here, whether you've never used git or you live in the terminal. Pick the path that fits you.

## Path A — I don't use git / GitHub much

You can do almost everything from the browser:

1. Open the file you want to change (e.g. a template under `docs/`).
2. Click the pencil icon (✏️) in the top-right of the file view — "Edit this file."
3. Make your changes.
4. Scroll down, add a short note about what you changed, and choose **"Create a new branch and start a pull request."**
5. Click **Propose changes**. That's it — a maintainer will review it.

Want to add a brand-new document (like a new proposal)? Go to the relevant folder (e.g. `docs/02-ideation`), click **Add file → Create new file**, and follow the same steps.

You don't need to know git, branches, or merge conflicts. If you get stuck, open an [Issue](../../issues/new/choose) instead and someone will help turn it into a doc.

## Path B — I'm comfortable with git

```bash
git clone <repo-url>
cd big-play
git checkout -b your-name/short-description
# make your changes
git add .
git commit -m "docs: add proposal for X"
git push origin your-name/short-description
# open a PR against main
```

## What to contribute, and where

| I want to... | Do this |
|---|---|
| Suggest a new idea/feature | Copy `docs/02-ideation/template-proposal.md` into a new file in that folder |
| Define what something must do | Copy `docs/01-requirements/template-requirement.md` into that folder |
| Record a decision that was made | Copy `docs/03-decisions/template-adr.md`, number it sequentially |
| Log a meeting | Copy `docs/05-meeting-notes/template-meeting-notes.md` |
| Fix a typo / clarify wording | Just edit the file directly (Path A above) — no proposal needed |

## Ground rules

- **Small, focused changes.** One proposal or one requirement per file/PR.
- **Write for the least technical reader who needs to understand it.** If a term needs jargon, add it to [`docs/00-overview/glossary.md`](docs/00-overview/glossary.md).
- **Don't overwrite others' open proposals** — comment on them or open a new one that references it instead.
- **Every PR gets at least one review** before merging — see [`GOVERNANCE.md`](GOVERNANCE.md) for who reviews what.

## Commit / PR message style

Keep it plain: `docs: <what changed>` — e.g. `docs: add proposal for offline mode`, `docs: fix broken link in roadmap`.

## Questions?

Open a [Discussion-style issue](.github/ISSUE_TEMPLATE/question.md) — no question is too basic.
