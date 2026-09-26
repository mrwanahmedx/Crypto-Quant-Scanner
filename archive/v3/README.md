# Crypto Scanner V3 — history record

**Status: DISCONTINUED / SUPERSEDED**  
**Artifact state: SOURCE ARTIFACT NOT RECOVERED — HISTORY ONLY**

V3 tightened the scanner around explicit regime, trigger and risk gates.

Recorded controls:
- Binance Spot, long-only, no leverage,
- BTC 4H regime filter,
- volume confirmation,
- reversal-candle hard gate,
- ATR-based stop geometry,
- minimum reward/risk of 2:1,
- position sizing capped at $20 for the then-small test account,
- expanded 19-coin watchlist,
- explicit NO TRADE outcome when gates were not met.

Testing exposed a smooth-trend failure in the fractal logic; an EMA fallback was added. That was useful engineering evidence, but it did not prove positive trading expectancy.

V3 was superseded by the stricter V4/V4.1 validation path. Exact source was not recovered and is not reconstructed here.
