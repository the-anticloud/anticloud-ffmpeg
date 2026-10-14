# Ethics — FFMPEG

**Project:** FFMPEG  
**Category:** MOVIES_MEDIA  
**Upstream:** see BENCH.json  
**Pinned commit:** `65aec1ff4dcd62a54c4361fe1719520378750c36`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `d8fc6035af0c6fc4c2874d6c3cb56e97df965cb956b7cbdbd481fb15b2625af5`  
**Date:** October 2026

## Position

FFMPEG is packaged for offline deployment with a verifiable audit trail. The
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
