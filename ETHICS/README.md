# Ethics — ENERGY_SPARKS

**Project:** ENERGY_SPARKS  
**Category:** ELECTRICITY_MANAGEMENT  
**Upstream:** https://github.com/energy-sparks/energy-sparks  
**Pinned commit:** `a1f60364d6ca9adec8e61a328dfad74fc03e5529`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `9eb4359718ebfd07bab2f5a1db95e2e95c84e91dd4688f2a71fe343d33d552c7`  
**Date:** October 2026

## Position

ENERGY_SPARKS is packaged for offline deployment with a verifiable audit trail. The
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
