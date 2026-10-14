# Educators — PYRESERVOIR

**Project:** PYRESERVOIR  
**Category:** OIL_GAS  
**Upstream:** https://github.com/yohanesnuwara/pyreservoir  
**Pinned commit:** `66b3aefe37413c19761598b8b7eefcd4debbb47e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a2fa84311b57b7fcec0b15db05cb8f2db922ca80fbd40000ee9079d0d507724c`  
**Date:** October 2026

## Teaching with PYRESERVOIR

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `a2fa84311b57b7fcec0b15db05cb8f2db922ca80fbd40000ee9079d0d507724c` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
