# Students — PYRESERVOIR

**Project:** PYRESERVOIR  
**Category:** OIL_GAS  
**Upstream:** https://github.com/yohanesnuwara/pyreservoir  
**Pinned commit:** `66b3aefe37413c19761598b8b7eefcd4debbb47e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a2fa84311b57b7fcec0b15db05cb8f2db922ca80fbd40000ee9079d0d507724c`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `66b3aefe37413c19761598b8b7eefcd4debbb47e`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `a2fa84311b57b7fcec0b15db05cb8f2db922ca80fbd40000ee9079d0d507724c`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
