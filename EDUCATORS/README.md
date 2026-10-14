# Educators — ENERGY_SPARKS

**Project:** ENERGY_SPARKS  
**Category:** ELECTRICITY_MANAGEMENT  
**Upstream:** https://github.com/energy-sparks/energy-sparks  
**Pinned commit:** `a1f60364d6ca9adec8e61a328dfad74fc03e5529`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9eb4359718ebfd07bab2f5a1db95e2e95c84e91dd4688f2a71fe343d33d552c7`  
**Date:** October 2026

## Teaching with ENERGY_SPARKS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `9eb4359718ebfd07bab2f5a1db95e2e95c84e91dd4688f2a71fe343d33d552c7` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
