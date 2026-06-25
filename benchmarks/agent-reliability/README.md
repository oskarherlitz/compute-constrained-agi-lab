# Agent reliability benchmark

Measure whether AI systems complete useful workflows reliably under cost constraints.

## North-star metric

**Cost per successful task** = cost per attempt ÷ success rate

## Planned workflows

| Workflow | Description |
|----------|-------------|
| Investment memo | Given company/market docs → memo, risks, diligence questions |
| DC permitting checklist | Given a hypothetical site → blockers, approvals, utility questions |
| Material market entry memo | Given property sheet + market notes → wedge market and pilot plan |

## Metrics (per run)

- Task success rate
- Critical omission rate
- Hallucination rate
- Cost per attempt
- Cost per successful task
- Human correction time

## Status

Not started. Will add `tasks/`, `results/`, and `evals.py` when benchmark v0 begins (target: week 5).
