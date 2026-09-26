# Crypto Scanner V4.1 — history record

**Status: DISCONTINUED — FAILED ELIGIBILITY FOR REAL-MONEY USE**  
**Artifact state: SOURCE ARTIFACT NOT RECOVERED — HISTORY ONLY**

V4.1 is the most important failed crypto generation because it reached a stricter validation stage and produced a clear negative result.

## Recorded gates

- bullish H4 regime requirement,
- bearish D1 block,
- volume-confirmed liquidity sweep,
- candle/reclaim trigger,
- relevant/recent FVG filtering,
- closed-candle logic,
- hard reward/risk gate.

A paper-update timestamp comparison bug using `>` was detected before freeze. It was changed to `>=` and a regression test was added.

## Validation record

- 36/36 tests passed before the timestamp defect was resolved.
- After the fix and regression coverage: **37/37 tests passed**.
- First frozen scan: **0 eligible trades, 0 logged entries**.
- Six-month / 18-symbol backtest: **14 signals, 2 wins, 12 losses**.
- Win rate: **14.29%**.
- Expectancy: **-0.9701R**.
- Profit factor: **0.2748**.
- Cumulative result: **-13.5817R**.
- Test suite later reached **43 passed**.
- Independent replay did not identify a look-ahead bug; even at zero transaction cost the result remained **-5.293R**.

## Conclusion

The implementation could pass its software tests while the strategy still failed economically. V4.1 therefore **failed eligibility for real-money deployment** and was not promoted.

The exact source artifact was not found in currently accessible saved files. This record preserves the failure honestly; source is not reconstructed or fabricated.
