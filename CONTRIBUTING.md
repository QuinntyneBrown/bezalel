# Contributing

How to contribute to the Bezalel repository — the idea, model, and playbooks, not a codebase.

## What kind of contributions this repo takes

This repository documents how Bezalel thinks and operates. Useful contributions include:

- Corrections to how the model, pipeline, or offerings are described
- New or improved playbooks based on real experience running discovery, hackathons, or engagements
- Additions to [`docs/engagements/`](docs/engagements/) once an engagement has actually happened
- Decision records in [`docs/decisions/`](docs/decisions/) when a real change is made to how Bezalel operates
- Clarifications to [`GLOSSARY.md`](GLOSSARY.md) when terminology is ambiguous or inconsistently used

## How to propose a change

1. Open an issue first for anything that changes the model, offerings, or guardrails — these are foundational and should be discussed before drafting.
2. For playbooks, engagement records, or glossary fixes, a pull request directly is fine.
3. Use the issue templates in [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE/) — `engagement-proposal.md` for proposing a new engagement, `initiative-task.md` for everything else.

## Writing conventions

- Markdown throughout, sentence-case headings.
- Every document opens with a one-line statement of what it is.
- Use relative links to reference other documents in this repo.
- Mark anything that needs founder input with `> TODO(quinn):` rather than inventing facts, especially FaithTech program details, real case-study specifics, or partner names.
- Keep writing concise and direct — assume the reader is a competent technologist deciding whether to give their time to this.

## Decision records

If you're proposing a change to how Bezalel fundamentally operates (not just wording), add an ADR-style entry to [`docs/decisions/`](docs/decisions/) following the format in `0001-adopt-bezalel-name.md`.
