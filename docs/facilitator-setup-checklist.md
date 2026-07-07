# Facilitator Setup Checklist

Use this checklist before learners begin Module 2 and when preparing continuity into Modules 3-5.

## Required before Module 2 lab

- Source repo is accessible in the Slalom org.
- Forking is enabled for this repository.
- Learners can fork and clone their copy.
- Seeded backlog content exists under `backlog/`.
- Seeded meeting summary exists under `meeting-notes/`.
- Seeded teammate review branch exists (`seed/teammate-review-request`).
- Canned reviewer comment is ready (`lab-assets/module-2/canned-review-comment.md`).

## Recommended validation run

- Run the learner flow once with a facilitator test account:
  - fork source repo
  - clone fork
  - create branch
  - update a user story
  - commit and push
  - open PR and confirm base is the learner fork `main`
- Run reviewer flow once:
  - open PR from `seed/teammate-review-request`
  - leave comment
  - approve and merge

## Continuity into Modules 3-5

- Module 3 starter artifacts: `specs/module-3/`.
- Module 4 connection notes: `integrations/module-4/`.
- Module 5 capstone seeds: `capstone/module-5/`.

The goal is one continuous learner repo journey rather than disconnected module-only exercises.
