# Web app

Next.js frontend for the Compute-Constrained AGI Lab.

Will host:

- Landing page and thesis
- Compute economics simulator
- Infrastructure atlas (later)
- Agent benchmark results (later)

## Setup (when ready)

```bash
npx create-next-app@latest . --typescript --tailwind --app --no-src-dir
```

Start with the simulator: GPU count, power, PUE, electricity price, utilization → facility MW, annual energy, annual cost.
