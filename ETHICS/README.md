# Ethics — TFEL

**Project:** TFEL  
**Category:** CHEMICAL_PRODUCTION  
**Upstream:** see BENCH.json  
**Pinned commit:** `ff3fa7eb3359ac67d532345c9971bcb1401c9f8f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3dfa7e5f48f2408e7e48eb0ebaccd402eb0767874eafb1b69dab67851dcc837a`  
**Date:** October 2026

## Position

TFEL is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
