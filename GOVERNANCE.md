# Governance

How decisions get made on Big Play, and by whom.

## Roles

| Role | Who | Can do |
|---|---|---|
| **Maintainer** | [list names/handles here] | Merge PRs, approve/reject proposals, final call on disputes |
| **Contributor** | Anyone who submits a PR/issue | Propose ideas, write requirements, comment/review |
| **Reviewer** (optional, can overlap with either above) | Assigned per area (e.g. design, technical feasibility) | Give required sign-off in their area before merge |

_Fill in real names next to each role once the team is confirmed._

## How a decision gets made

1. **Raise it** — as a proposal (`docs/02-ideation`) if it's a new idea, or directly as an issue if it's small.
2. **Discuss it** — in the PR/issue thread. Anyone can weigh in; give it at least a few days unless it's urgent.
3. **Decide it**:
   - Small/reversible decisions: any maintainer can approve.
   - Larger/structural decisions (things that would be costly to undo): needs sign-off from a majority of maintainers, and should be recorded as an [ADR](docs/03-decisions).
4. **Record it** — significant decisions get written down as an ADR so future contributors know *why*, not just *what*.

## Disagreements

If discussion stalls or people can't agree, a maintainer makes the final call and documents the reasoning in the ADR. The goal is forward progress, not unanimous agreement on everything.

## Changing this document

Governance changes go through the same proposal process as anything else — open a proposal in `docs/02-ideation` describing what you'd change and why.
