# Assumptions

This project uses **ranges, not false precision**. Every model input should have a low / base / high estimate and a source or rationale.

## Policy

- Publish assumptions alongside outputs.
- Prefer sourced public data over hand-wavy point estimates.
- Update this file when expert conversations or new data change your beliefs.
- If a number is illustrative only, say so.

## Facility / energy

| Variable | Base | Range | Source / notes |
|----------|------|-------|----------------|
| PUE | 1.25 | 1.1 – 1.5 | Hyperscale vs. older facilities |
| Electricity price ($/kWh) | 0.08 | 0.04 – 0.15 | Varies heavily by region; use atlas data when available |
| Annual operating hours | 8,760 | — | Full year |
| GPU utilization | 0.6 | 0.3 – 0.9 | Training vs. inference workloads differ |

## Compute

| Variable | Base | Range | Source / notes |
|----------|------|-------|----------------|
| GPU power draw (W) | — | — | GPU-specific; see presets in simulator |
| GPU hourly cost ($) | — | — | Cloud/on-prem varies; cite source when set |
| Tokens per request | 2,000 | 500 – 8,000 | Task-dependent |

## Reliability / economics

| Variable | Base | Range | Source / notes |
|----------|------|-------|----------------|
| Task success rate | 0.7 | 0.3 – 0.95 | Agent workflows; benchmark will inform |
| Human correction time (min) | 10 | 0 – 60 | Per failed or partial task |

## Known limitations

- Training FLOPs estimates are approximate; use for scenario comparison, not capex decisions.
- Regional infrastructure scores are preliminary proxies, not engineering assessments.
- Benchmark rubrics reflect one evaluator's judgment until expanded.

## Changelog

| Date | Change |
|------|--------|
| — | Initial template |
