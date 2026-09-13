# cert-manager

[中文版本](./README.cn.md)

Automatically provision and manage TLS certificates in Kubernetes

![cert-manager](https://repo.x-cmd.io/cert-manager.svg)

## Install

```sh
x install cert-manager
```

## Code insight

Total: **218,630** lines of code across **1099** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 180,860 | 34,750 | 20,870 | 938 |
| Yaml | 31,873 | 1,452 | 552 | 101 |
| Json | 2,601 | 0 | 0 | 6 |
| Makefile | 1,820 | 1,408 | 530 | 33 |
| Sh | 965 | 566 | 306 | 21 |

## OpenSSF Scorecard

Overall score: **8.4 / 10**

Lowest-scoring checks:

- **Packaging** (-1/10) — packaging workflow not detected
- **Signed-Releases** (0/10) — Project has not signed or included provenance with any releases.
- **SAST** (0/10) — SAST tool is not run on all commits -- score normalized to 0

## Source

- **Upstream**: <https://github.com/cert-manager/cert-manager>
- **Homepage**: <https://cert-manager.io>
- **License**: Apache-2.0

## Release

- **Latest**: `v1.21.2` (2026-09-11)
- **Last commit**: 2026-09-12
- **Assets in release**: 2

## Popularity

- **Stars**: 14,077 · **Forks**: 2,449 · **Open issues**: 3,819 · **Contributors**: 533

## Totals (cumulative)

- **Releases**: 256 · **Merged PRs**: 4181 · **Open PRs**: 105 · **Closed issues**: 3661 · **Open issues**: 158 · **Commits**: 11395

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-14 | 1 | 120 | 36 | 16 | 17 | 153 |
| last60d | 2026-07-15 | 2 | 186 | 47 | 24 | 26 | 274 |
| 90d | 2026-06-15 | 6 | 288 | 54 | 32 | 34 | 415 |
| last180d | 2026-03-17 | 11 | 448 | 69 | 57 | 50 | 739 |
| 360d | 2025-09-18 | 25 | 800 | 89 | 124 | 83 | 1447 |
| last720d | 2024-09-23 | 51 | 1203 | 101 | 312 | 120 | 2303 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [cert-manager.crds.yaml](https://github.com/cert-manager/cert-manager/releases/download/v1.21.2/cert-manager.crds.yaml) | 973.7 KiB | `other` |
| [cert-manager.yaml](https://github.com/cert-manager/cert-manager/releases/download/v1.21.2/cert-manager.yaml) | 1010.2 KiB | `other` |

## Improve this data

Install metadata for cert-manager lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `cert-manager` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/cert-manager.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260913.yml` · 2026-09-13T05:14:34Z._
