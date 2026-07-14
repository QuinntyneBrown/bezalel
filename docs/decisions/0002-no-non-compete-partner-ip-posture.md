# 0002. No non-compete; protect partners through IP posture instead

## Status

Accepted

## Context

FaithTech forms partnerships with infrastructure organizations and other orgs that mission partners can benefit from — hosting, cloud, tooling, and professional services offered as backing (see the definition of **backing partner** in [`GLOSSARY.md`](../../GLOSSARY.md)). A recurring question is whether Bezalel needs a **non-compete** to protect its interests, particularly where a mission partner's software ends up hosted or managed by one of those partner organizations.

A non-compete is the wrong instrument here, for three reasons:

1. **There is nothing a non-compete is built to protect.** A non-compete restrains a party from competing with a business. Bezalel is not a legal entity, consultancy, or vendor; it has no clients and charges no fees ([`docs/model/operating-model.md`](../model/operating-model.md), [`docs/model/guardrails.md`](../model/guardrails.md)). There is no revenue stream or market position for a competitor to erode.

2. **There is no one it could bind.** Practitioners are volunteers and community members, not employees. Bezalel operates in Toronto, where Ontario's *Working for Workers Act, 2021* bans employee non-competes and renders them generally unenforceable. Even if the model wanted one, it could not bind the people it would need to.

3. **It contradicts the model's own values.** A non-compete is a lock-in mechanism. Bezalel explicitly rejects "technology that entrenches a partner's dependency… rather than building their capacity to operate independently," requires a documented handoff, and holds that mission partners "can say no, pause, or exit a project at any point" ([`docs/model/guardrails.md`](../model/guardrails.md)). A non-compete would adopt the opposite posture toward the very partners the model exists to free.

The real risk behind the question is not competition. It is **conflict of interest and lock-in through the back door**: a backing or infrastructure partner that hosts or manages a mission partner's code could gain leverage over that partner, or steer the project toward its own platform. That risk is real, but it is addressed by clarifying ownership, portability, and conflict-of-interest — not by restraining anyone from competing.

## Decision

1. **Bezalel adopts no non-compete** — not against practitioners, mission partners, backing partners, or infrastructure partners.

2. Bezalel protects its interests and, more importantly, its partners' interests through **IP posture and portability**, formalized as guardrails:
   - Mission partners own the software built for them and their data (existing principle, now made explicit).
   - Built software is released under an open-source license by default, so a mission partner can always leave any infrastructure or backing partner and take their code with them. The specific license is deferred to a follow-up decision (see Consequences).
   - Practitioners contribute their work under clear contribution terms (license or assignment) with attribution, so ownership can be transferred cleanly to the mission partner.

3. Bezalel adds a **conflict-of-interest guardrail** for backing and infrastructure partners: where a backing partner also stands to benefit commercially from hosting or managing the software (or from the mission partner adopting its platform), that interest must be disclosed, the partner may not steer product or architecture decisions toward it, and the mission partner's ownership and exit rights are never conditioned on staying with that partner.

These commitments are recorded in [`docs/model/guardrails.md`](../model/guardrails.md).

## Consequences

- Bezalel does not gate participation, partnership, or continuation on any non-compete, and will not ask practitioners or partners to sign one.
- The load-bearing protection shifts to licensing. Choosing the default open-source license for built software (e.g., a permissive license such as MIT/Apache-2.0 versus a copyleft license such as AGPL) is now a required follow-up decision; it should be recorded as its own decision record and reconciled with the outstanding repository-license `TODO(quinn)` in [`README.md`](../../README.md).
- Backing and infrastructure partnerships remain welcome and are made *safer* to enter, because the terms that protect the mission partner are explicit rather than implied.
- Reviewers of a proposed continuation project can point to a written conflict-of-interest guardrail when a backing partner's platform interest is in play, rather than adjudicating it case by case.

> TODO(quinn): add the date this decision was made and who was involved, and open the follow-up decision selecting the default software license.
