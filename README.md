# Evidence-led marketing agent

An agent skill for marketing and go-to-market work that has to hold up in front of a skeptical reader: a founder, a hiring panel, a client who will check your sources.

It sits on top of the 40-odd specialist skills in [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) and adds the part those skills leave to you: deciding what question the work answers, ranking evidence, keeping company claims apart from proof, and attacking its own draft before you see it.

I wrote it alongside a GTM take-home I did with Codex ([the case](https://yixiang-li.github.io/fullive-gtm-case/)). What mattered in that case were a few calls a fast first pass gets wrong. Is Sleep.ai a competitor, or a possible partner for proving the product works? Should the landing page lead with multisensory novelty, which a competitor already promises, or with how the evening feels? This skill turns that kind of checking into steps an agent follows every time.

## What it makes the agent do

1. **Start from the decision.** State the decision, the audience, the time box and the deliverables, and what evidence could change the answer.
2. **Route to specialist skills.** Pick the smallest useful set from the marketingskills modules (positioning, competitor profiling, pricing, CRO, analytics, launch…) and read each one in full before using it. See [`references/module-map.md`](references/module-map.md).
3. **Keep a claim ledger.** Every claim gets a source, a date, a type (verified fact, company claim, external evidence, inference) and a confidence. AI output is never a source. See [`references/evidence-standard.md`](references/evidence-standard.md).
4. **Challenge the draft.** Generate, verify, look for counter-evidence, reclassify, rewrite, and record at least two before-and-after corrections for the AI workflow note.
5. **Ship a consistent stack.** Research log, deck or report, landing page copy and measurement plan all use the same segments and positioning, and every caveat stays in the main body.

For timed take-homes there is a separate playbook: [`references/marketing-case-playbook.md`](references/marketing-case-playbook.md).

## Install

Codex:

```bash
git clone https://github.com/Yixiang-Li/evidence-led-marketing-agent ~/.codex/skills/evidence-led-marketing-agent
```

Claude Code:

```bash
git clone https://github.com/Yixiang-Li/evidence-led-marketing-agent ~/.claude/skills/evidence-led-marketing-agent
```

Install [marketingskills](https://github.com/coreyhaines31/marketingskills) the same way so the specialist modules are available. Then ask for the work in plain language, for example:

```text
Use evidence-led-marketing-agent. We sell a $349 AI sleep device in the US.
Compare it with the 6–8 products a buyer would weigh it against, with dated
first-party prices, and tell me which positioning to test first.
```

## Files

| File | What it holds |
| --- | --- |
| [`SKILL.md`](SKILL.md) | The workflow the agent follows |
| [`references/evidence-standard.md`](references/evidence-standard.md) | Evidence classes, source hierarchy, confidence labels |
| [`references/module-map.md`](references/module-map.md) | Which marketingskills module to use for what |
| [`references/marketing-case-playbook.md`](references/marketing-case-playbook.md) | How to run a timed case or take-home |
| [`agents/openai.yaml`](agents/openai.yaml) | Display name and default prompt for Codex |

Made by [Yixiang Li](https://github.com/Yixiang-Li).
