# Compute-Constrained AGI Lab

How do we maximize useful intelligence under real-world constraints such as compute, power, capital, latency, trust, and deployment?

This repo is a public research and build project about the production function of useful intelligence

## Artifacts (in progress)

| Artifact | Status | Location |
|----------|--------|----------|
| Compute economics simulator | Planned | `apps/web/`, `notebooks/simulator-v0.ipynb` |
| AI infrastructure atlas | Planned | — |
| Agent reliability benchmark | Planned | `benchmarks/agent-reliability/` |
| Founder memo | Planned | `docs/` |

## Repo structure

```
compute-constrained-agi-lab/
  README.md
  docs/
    thesis-v0.md          # Core thesis
    assumptions.md        # Model assumptions and ranges
    build-logs/           # Weekly public updates
  apps/
    web/                  # Next.js frontend (simulator, atlas, site)
  notebooks/
    simulator-v0.ipynb    # Early simulator exploration
  data/
    sample-scenarios.json # Example compute/energy scenarios
  benchmarks/
    agent-reliability/    # Cost-per-success evaluation
```

## North-star metric

**Useful intelligence per watt-dollar** — and its deployment cousin, **cost per successful task**.

## Getting started

### Python / notebooks

```bash
python3.13 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

In Cursor, open `notebooks/simulator-v0.ipynb` and select the kernel:
**.venv (Python 3.13)** — not the global Homebrew Python 3.14.

### Explore

1. Read `docs/thesis-v0.md` and `docs/assumptions.md`.
2. Open `notebooks/simulator-v0.ipynb` to explore facility economics.
3. See `data/sample-scenarios.json` for example inputs.
