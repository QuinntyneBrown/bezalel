# Guardrails

The ethical and economic lines the Bezalel experiment holds: what it will and won't build, and how it protects mission partners, backing partners, and practitioners.

## Projects the model can take on

Technology that meets the redemptive frame in [`docs/vision/redemptive-frame.md`](../vision/redemptive-frame.md): targets real repair, is built with integrity of means, and is built to last.

## Projects the model will reject

- Technology whose primary value depends on exploiting user attention, data, or trust (engagement-maximizing design, dark patterns, undisclosed data resale).
- Technology that entrenches a partner's dependency on Bezalel rather than building their capacity to operate independently — see the handoff requirement in [`docs/model/the-pipeline.md`](the-pipeline.md).
- Surveillance or control systems aimed at congregants, staff, or vulnerable populations without their informed knowledge and consent.
- Work that requires practitioners to compromise their own technical or ethical standards to hit a deadline — a rushed, undocumented, untested system handed to a partner who cannot maintain it is a guardrail violation, not just a quality miss.

> TODO(quinn): add any additional specific exclusions (e.g., categories of partner request you've already had to decline) so future leads have precedent to point to.

## Protecting partners

- Mission partners are not clients and are not charged a service fee for Bezalel work.
- No project proceeds without discovery — a mission partner's stated solution is a starting hypothesis, not a spec.
- Partners retain ownership of their data and, by default, the software built for them.
- Built software is released under an open-source license by default, so a mission partner can always leave any infrastructure or backing partner and take their code with them. (The specific default license is a pending decision.)
- Every project ends with a documented handoff: mission partners should never be left holding a system only the build team understands.
- Mission partners can say no, pause, or exit a project at any point without it being treated as a failure.
- Backing partners cannot buy priority, weaken the redemptive criteria, or dictate product decisions that belong to the mission partner and project team.
- Bezalel uses **no non-compete** — against practitioners, mission partners, or backing partners. Partner interests are protected through ownership, portability, and the conflict-of-interest guardrail below, not by restraining anyone from competing. See [`docs/decisions/0002-no-non-compete-partner-ip-posture.md`](../decisions/0002-no-non-compete-partner-ip-posture.md).

## Backing and infrastructure partners: conflict of interest

FaithTech forms partnerships with infrastructure organizations and other orgs whose hosting, tooling, or services mission partners can benefit from. Where a backing or infrastructure partner also stands to benefit commercially from hosting or managing the software — or from the mission partner adopting its platform:

- That interest must be **disclosed** to the mission partner and the project team.
- The partner may **not steer** product or architecture decisions toward its own platform; those decisions belong to the mission partner and project team.
- The mission partner's **ownership and exit rights are never conditioned** on staying with that partner. Code and data must remain portable, so "managed by partner X" never becomes "trapped at partner X."

## Protecting practitioners

- Practitioner time, whether volunteered or funded by a backing partner, is treated as a real, finite resource, not something to be extracted because the cause is good.
- No practitioner is asked to work outside their competence without support — under-scoped, over-promised projects put both the mission partner and the practitioner's growth at risk.
- Practitioners are credited for their work in project records.

> TODO(quinn): add specific commitments around burnout prevention, backing-partner conflicts, funded practitioner roles, expenses, and IP/attribution.
