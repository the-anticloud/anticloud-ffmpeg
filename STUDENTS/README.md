# Students — FFMPEG

**Project:** FFMPEG  
**Category:** MOVIES_MEDIA  
**Upstream:** see BENCH.json  
**Pinned commit:** `65aec1ff4dcd62a54c4361fe1719520378750c36`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `d8fc6035af0c6fc4c2874d6c3cb56e97df965cb956b7cbdbd481fb15b2625af5`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `65aec1ff4dcd62a54c4361fe1719520378750c36`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `d8fc6035af0c6fc4c2874d6c3cb56e97df965cb956b7cbdbd481fb15b2625af5`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
