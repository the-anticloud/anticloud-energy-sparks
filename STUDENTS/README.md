# Students — ENERGY_SPARKS

**Project:** ENERGY_SPARKS  
**Category:** ELECTRICITY_MANAGEMENT  
**Upstream:** https://github.com/energy-sparks/energy-sparks  
**Pinned commit:** `a1f60364d6ca9adec8e61a328dfad74fc03e5529`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9eb4359718ebfd07bab2f5a1db95e2e95c84e91dd4688f2a71fe343d33d552c7`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `a1f60364d6ca9adec8e61a328dfad74fc03e5529`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `9eb4359718ebfd07bab2f5a1db95e2e95c84e91dd4688f2a71fe343d33d552c7`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
