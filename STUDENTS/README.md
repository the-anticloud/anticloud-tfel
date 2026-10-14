# Students — TFEL

**Project:** TFEL  
**Category:** CHEMICAL_PRODUCTION  
**Upstream:** see BENCH.json  
**Pinned commit:** `ff3fa7eb3359ac67d532345c9971bcb1401c9f8f`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3dfa7e5f48f2408e7e48eb0ebaccd402eb0767874eafb1b69dab67851dcc837a`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `ff3fa7eb3359ac67d532345c9971bcb1401c9f8f`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `3dfa7e5f48f2408e7e48eb0ebaccd402eb0767874eafb1b69dab67851dcc837a`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
