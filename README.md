# Crypto Quant Scanner — Discontinued Research

This repository is retained as a **research-history placeholder**, not as a working trading product.

## Status

**Discontinued / not validated for live use.**

No current scanner implementation in this repository has passed the evidence standard required for a public quantitative model. The repository therefore makes **no claim of predictive edge, backtested profitability, or production readiness**.

## Why keep the repository?

Failed and discontinued research can still be useful evidence of process when its status is explicit.

The intended research standard is:

```text
market data
  ↓
quality / provenance checks
  ↓
feature and target definition
  ↓
leakage-safe validation
  ↓
cost-aware evaluation
  ↓
acceptance gates
  ↓
only then: live / shadow consideration
```

If an implementation cannot pass those gates, the correct outcome is to document the failure or blocker rather than present it as a functioning scanner.

## Archived version history

The known scanner lineage is now organized under [`archive/`](archive/README.md):

- **V1** — early BTC multi-timeframe dashboard; discontinued.
- **V2** — multi-coin structure/FVG/sweep scanner; scoring was not empirically derived.
- **V3** — harder regime/volume/candle/R:R gates; superseded.
- **V4 / V4.1** — stricter closed-candle and paper-validation path; **V4.1 failed real-money eligibility** in its six-month / 18-symbol backtest.

The exact source packages were not recoverable from the currently accessible saved artifacts, so these are intentionally **history-only records**. No missing code has been recreated from memory.

## Current repository contents

There is currently **no validated scanner code published here**. The repository does contain the documented historical lineage under [`archive/`](archive/README.md), including the negative V4.1 validation result.

Any future revival should start from a documented data contract and validation protocol rather than from an unverified signal script.

## Related active research

The more developed research framework is:

**[EGX Quant Research](https://github.com/mrwanahmedx/EGX-Quant-Research)**

That repository demonstrates the stronger standard: point-in-time controls, data-quality gates, holdout protection, model registries, execution assumptions, and explicit refusal to promote models when the evidence is insufficient.

## Disclaimer

Research only. Not investment advice.
