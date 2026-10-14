# Educators — TFEL

**Project:** TFEL  
**Category:** CHEMICAL_PRODUCTION  
**Upstream:** see BENCH.json  
**Pinned commit:** `ff3fa7eb3359ac67d532345c9971bcb1401c9f8f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3dfa7e5f48f2408e7e48eb0ebaccd402eb0767874eafb1b69dab67851dcc837a`  
**Date:** October 2026

## Teaching with TFEL

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `3dfa7e5f48f2408e7e48eb0ebaccd402eb0767874eafb1b69dab67851dcc837a` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
