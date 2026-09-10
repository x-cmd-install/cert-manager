# cert-manager

[中文版本](./README.cn.md)

Automatically provision and manage TLS certificates in Kubernetes

![cert-manager](https://repo.x-cmd.io/cert-manager.svg)

## Install

```sh
x install cert-manager
```

## Source

- **Upstream**: <https://github.com/cert-manager/cert-manager>
- **Homepage**: <https://cert-manager.io>
- **License**: Apache-2.0

## Release

- **Latest**: `v1.21.1` (2026-07-29)
- **Last commit**: 2026-09-10
- **Assets in release**: 2

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [cert-manager.crds.yaml](https://github.com/cert-manager/cert-manager/releases/download/v1.21.1/cert-manager.crds.yaml) | 973.7 KiB | `other` |
| [cert-manager.yaml](https://github.com/cert-manager/cert-manager/releases/download/v1.21.1/cert-manager.yaml) | 1010.2 KiB | `other` |

## Popularity

- **Stars**: 14,075 · **Forks**: 2,445 · **Open issues**: 3,818 · **Contributors**: 533

## Totals (cumulative)

- **Releases**: 255 · **Merged PRs**: 4176 · **Open PRs**: 99 · **Closed issues**: 3659 · **Open issues**: 159 · **Commits**: 11386

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 0 | 131 | 28 | 16 | 18 | 189 |
| 90d | 2026-06-12 | 5 | 288 | 48 | 31 | 35 | 447 |
| 360d | 2025-09-15 | 24 | 802 | 83 | 125 | 85 | 1460 |

## Code size

Total: **218,695** lines of code across **1100** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 180,860 | 34,750 | 20,870 | 938 |
| Yaml | 31,873 | 1,452 | 552 | 101 |
| Json | 2,601 | 0 | 0 | 6 |
| Makefile | 1,821 | 1,410 | 531 | 33 |
| Sh | 1,029 | 648 | 322 | 22 |

## OpenSSF Scorecard

Overall score: **8.4 / 10**

Lowest-scoring checks:

- **Packaging** (-1/10) — packaging workflow not detected
- **SAST** (0/10) — SAST tool is not run on all commits -- score normalized to 0
- **Branch-Protection** (-1/10) — internal error: error during branchesHandler.setup: internal error: some github tokens can't read classic branch protect…

## Improve this data

Install metadata for cert-manager lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `cert-manager` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/cert-manager.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T16:49:07Z._
