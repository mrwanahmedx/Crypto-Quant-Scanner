# Crypto Scanner V4 — history record

**Status: DISCONTINUED / SUPERSEDED BY V4.1**  
**Artifact state: SOURCE ARTIFACT NOT RECOVERED — HISTORY ONLY**

V4 moved away from loose composite scoring toward a gated process:

`regime -> setup -> trigger -> risk -> validation`

Recorded design direction included:
- retaining sweep/reclaim confirmation,
- requiring stronger structural reclaim behavior,
- using closed-candle evidence,
- adding paper-trade logging rather than direct order execution.

The exact V4 source package was not recovered. The design was hardened into V4.1, whose backtest ultimately failed the real-money eligibility gate.
