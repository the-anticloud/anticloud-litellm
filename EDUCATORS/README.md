# Educators — LITELLM

**Project:** LITELLM  
**Category:** FRONTIER_HARNESSES  
**Upstream:** see BENCH.json  
**Pinned commit:** `53bfd20e2fec51fc8f665fb614512c6b138367da`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `c1869993ce39aaadeedbbe31b096682422564adbd5dba0c273081b867f15a2f2`  
**Date:** October 2026

## Teaching with LITELLM

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `c1869993ce39aaadeedbbe31b096682422564adbd5dba0c273081b867f15a2f2` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
