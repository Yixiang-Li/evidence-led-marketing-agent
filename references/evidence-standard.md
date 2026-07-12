# Evidence and AI Output Standard

## Evidence Classes

Label important material as one of four classes:

1. **Verified fact**: Directly supported by an authoritative source for that fact.
2. **Company claim**: Stated by the company but not independently validated.
3. **External evidence**: Independent research, reporting, measured review data, or customer evidence.
4. **Inference or hypothesis**: Analyst interpretation that requires validation.

Do not silently upgrade one class into another.

## Source Hierarchy

Choose the source closest to the claim:

1. Official product, pricing, policy, regulatory, filing, or help-center pages.
2. Peer-reviewed research, government, standards bodies, and recognized professional institutions.
3. Reputable independent reporting, analyst work, or transparent datasets.
4. Review platforms and communities for sentiment and verbatim language, with sample-bias caveats.
5. Search snippets and aggregators only for discovery.
6. AI output is never a final source.

One first-party source can establish the company's current price or stated positioning. It cannot independently prove efficacy, market leadership, or customer outcomes.

## Claim Ledger

Use these columns in a spreadsheet or research log:

| Field | Purpose |
|---|---|
| Claim ID | Stable reference such as C-01 |
| Decision use | Why this claim matters |
| AI draft | Initial generated or discovered wording |
| Final claim | Corrected decision-ready wording |
| Evidence class | Fact, company claim, external evidence, or inference |
| Primary source | URL, owner, title, and access date |
| Secondary source | Independent corroboration where needed |
| Conflict or caveat | Disagreement, stale data, methodology, or sample bias |
| Confidence | High, medium, or low with a short reason |
| Implication | What changes because of this evidence |

## Verification Rules

- Time-stamp pricing, people, product specifications, market status, partnerships, and policies.
- Use comparable price bases: list versus promotion, hardware versus subscription, per month versus annual, and required versus optional fees.
- Verify quotations against the original source and preserve context.
- For weaknesses, use review patterns or label product-design deductions as inference.
- For surveys and review mining, report sample size, source mix, recency, and likely bias.
- For scientific or medical-adjacent claims, inspect study ownership, design, population, outcome, and whether the claim is causal.
- Preserve unresolved conflicts and state which source would resolve them.

## Synthesis Rules

- Compare competitors by the customer job and substitute behavior, not shared keywords.
- Separate direct, secondary, indirect, and component benchmarks.
- Normalize fields before ranking or scoring.
- Do not average incompatible segments.
- Prioritize differences that change positioning, audience, pricing, channel, conversion, or product decisions.
- End each analytical section with an implication and next action.

## AI Improvement Log

Record at least two material examples:

| Stage | Example |
|---|---|
| AI draft | `Oura is a direct sleep-improvement competitor.` |
| Verification | Official materials emphasize tracking and personalized insights, not control of the sleep environment. |
| Challenge | The shared job is better sleep, but the intervention mechanism and purchase category differ. |
| Improved output | `Treat Oura as an adjacent benchmark for data trust and personalization, not a direct environmental-intervention competitor.` |

Prefer examples where verification changed classification, wording, priority, pricing, or recommendation. Grammar edits do not demonstrate judgment.

## Confidence Calibration

- **High**: Authoritative, current, directly measured, and consistent across relevant sources.
- **Medium**: Supported but indirect, self-reported, limited to one segment, or partly conflicting.
- **Low**: Sparse, stale, single-source, inferred, or materially unresolved.

State what evidence would raise or lower confidence.
