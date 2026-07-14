# Contributing

How to contribute to the Bezalel repository — the idea, model, and playbooks, not a codebase.

## What kind of contributions this repo takes

This repository documents the model FaithTech Toronto is exploring through Bezalel. Useful contributions include:

- Corrections to how the model, pipeline, or program activities are described
- New or improved playbooks based on real experience running Create, discovery, hackathons, or continuation projects
- Additions to [`docs/engagements/`](docs/engagements/) once a partner project has actually happened
- Decision records in [`docs/decisions/`](docs/decisions/) when a real change is made to the model
- Clarifications to [`GLOSSARY.md`](GLOSSARY.md) when terminology is ambiguous or inconsistently used

## How to propose a change

1. Open an issue first for anything that changes the model, program activities, or guardrails — these are foundational and should be discussed before drafting.
2. For playbooks, project records, or glossary fixes, a pull request directly is fine.
3. Use the issue templates in [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE/) — `engagement-proposal.md` for proposing a continuation project, `initiative-task.md` for everything else.

## Writing conventions

- Markdown throughout, sentence-case headings.
- Every document opens with a one-line statement of what it is.
- Use relative links to reference other documents in this repo.
- Mark anything that needs founder input with `> TODO(quinn):` rather than inventing facts, especially FaithTech program details, real case-study specifics, or partner names.
- Keep writing concise and direct — assume the reader is a competent technologist deciding whether to give their time to this.

## Decision records

If you're proposing a fundamental change to the Bezalel model (not just wording), add an ADR-style entry to [`docs/decisions/`](docs/decisions/) following the format in `0001-adopt-bezalel-name.md`.
