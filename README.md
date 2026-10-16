# FFMPEG

> FFmpeg is a collection of libraries and tools to process multimedia content such as audio, video, subtitles and related metadata.

**Category:** MOVIES_MEDIA · **Ecosystem:** unknown · **Vendored upstream:** https://github.com/FFmpeg/FFmpeg · **Pinned commit:** `3c92f003c7d1a249cd921a74e5b22297e1368014` · **Vendor:** Anticloud FZ LLE

## What This Project Is

FFmpeg is a collection of libraries and tools to process multimedia content such as audio, video, subtitles and related metadata.

This is the upstream project, vendored at the pinned commit above and packaged offline-first. The 12 improvements Anticloud adds live in `anticloud/` and are described under *Anticloud Overlay* below. Every fact in this file traces to a file in this directory.

## Installation

```
# See the upstream README (linked above) for build steps.
```

## Usage

Coding examples are available in the **doc/examples** directory.

## Anticloud Overlay

The 12 improvements live under `anticloud/`. Run the check suite from this directory:

```
python anticloud/bench/runner.py --cwd anticloud
```

## Benchmark Results

The suite is recorded in `BENCH.json`; no benchmark rows were found in this package.

## Licence

The upstream licence is preserved in `LICENSE` and `THIRD_PARTY_LICENSES/`. The Anticloud overlay is licensed under Anticommons 0.1.0 (`ANTICOMMONS_LICENSE.md`).

## Verification

SHA3-256 of `BENCH.json`:

```
668ded6faabcde8bb296e1587dec76c93e8ed653a46d61cbb742b642dece9c3e
```

Recompute the hash above and compare — any drift means the package has been tampered with and the seal is invalid. This is a self-assessment; no external audit has been performed and a SOC 2 / NIST independent audit is committed post-funding.
