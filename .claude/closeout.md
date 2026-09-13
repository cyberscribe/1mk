# Closeout conventions — 1MK (One-Man Kanban)

Read by the `closeout` plugin in Claude Code and the `closeout` skill in Cowork. The generic
procedure comes from the plugin; this file is the seasoning.

This project already has a working memory convention and it governs. Nothing here replaces it.

## Promotion tiers

| Type | Test | Destination here |
|---|---|---|
| Working standards | Changes how work on the manifesto is done | `CLAUDE.md` |
| General reference | Durable context about the project | A new file under `memory/`, plus a one-line pointer in `memory/MEMORY.md` |
| Draft state | What is written versus placeholder | `memory/project_1mk_raw_notes_state.md` |
| The argument itself | The manifesto's actual content | `raw-notes.md` |

`memory/MEMORY.md` is an index: one line per entry, a pointer and the hook that says when it matters.
A new file under `memory/` gains its line in the same pass. A paragraph in the index belongs in the
file the line points at.

**Nothing 1MK goes to the global auto-memory location.** That folder may hold a single pointer back
here and nothing more. A promotion into a personal memory store reaches nobody and no other surface —
it feels like filing and is closer to deletion with extra steps.

## Re-read before acting

`raw-notes.md` changes faster than any snapshot of it. Read it, not
`memory/project_1mk_raw_notes_state.md`, before making a claim about what is drafted. The snapshot is
a convenience that goes stale by design; treating it as current is how a closeout records a finding
about a draft that has since moved.

## The vocabulary is load-bearing

**Outcome** replaces GTD *Project*. **Deliverable** is an artifact, AI- or human-produced. **State of
Play** replaces *Next Action*. Plus **Mind Dump** and **Weekly Retrospective**. Full mapping and
reasoning in `memory/project_1mk_manifesto.md`.

A promotion written in GTD's vocabulary rather than 1MK's quietly undoes the argument the manifesto is
making. Write promotions in the project's own terms.

## The AI / no-AI split is a constraint, not a preference

Working memory and mind dumps are **not** shared with AI. Everything else is. A closeout does not
promote, quote, or summarise material from the no-AI side, and does not propose a workflow that would
route it through an agent. This is part of the argument the manifesto makes, so violating it in the
course of writing the manifesto is a specific kind of failure.

## Register

Manifesto, not how-to guide. Robert is making an argument. A promotion that softens a claim into
guidance has changed the book.

## Cross-project promotion

Strip out 1MK, the manifesto, GTD and the path. If the entry still means something, it belongs in
`~/workspace/logs/decisions.md` and goes to Robert either way. 1MK's relationship to the posture
venture — sibling, a lighter heretical break from GTD, with the posture layer methodology-agnostic —
is already recorded in `memory/project_1mk_manifesto.md`; add to it there rather than restating it.

## Tracking is reconciled, not promoted

Chapter status and what is outstanding are state. Promote learnings first, reconcile state second,
and report the two separately.
