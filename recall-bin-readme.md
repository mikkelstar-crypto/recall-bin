# recall-bin

Release builds of **recall** (session recall for Claude Code). One file, `recall.pyz`, runs with
Python >= 3.11. The source is private; this repository holds only this readme and the releases.

## Install

    curl -fsSLo recall.pyz https://github.com/mikkelstar-crypto/recall-bin/releases/latest/download/recall.pyz
    python3 recall.pyz --version

A specific version: `.../releases/download/v1.0.0/recall.pyz`.

## Versions

Every release here has the same version, tag and changelog section as the private source repo:
`recall --version` prints it, and the release notes are the changelog entry. 1.0.0 (2026-11-06)
is the first official release; 0.3.0–0.5.2 are the earlier development builds.
