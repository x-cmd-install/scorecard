# scorecard

[中文版本](./README.cn.md)

OpenSSF Scorecard - Security health metrics for Open Source

![scorecard](https://repo.x-cmd.io/scorecard.svg)

## Install

```sh
x install scorecard
```

## Code insight

Total: **84,216** lines of code across **753** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 78,117 | 11,634 | 8,154 | 593 |
| Yaml | 4,231 | 1,700 | 328 | 149 |
| Svg | 810 | 2 | 0 | 5 |
| Makefile | 338 | 57 | 72 | 1 |
| Bash | 156 | 51 | 34 | 5 |

## OpenSSF Scorecard

Overall score: **9 / 10**

Lowest-scoring checks:

- **Branch-Protection** (-1/10) — internal error: error during branchesHandler.setup: internal error: some github tokens can't read classic branch protect…
- **Vulnerabilities** (0/10) — 43 existing vulnerabilities detected

## Source

- **Upstream**: <https://github.com/ossf/scorecard>
- **Homepage**: <https://scorecard.dev>
- **License**: Apache-2.0

## Release

- **Latest**: `v5.5.0` (2026-04-23)
- **Last commit**: 2026-09-08
- **Assets in release**: 8

## Popularity

- **Stars**: 5,686 · **Forks**: 721 · **Open issues**: 1,263 · **Contributors**: 209

## Totals (cumulative)

- **Releases**: 48 · **Merged PRs**: 2996 · **Open PRs**: 66 · **Closed issues**: 875 · **Open issues**: 388 · **Commits**: 3106

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 1 | 26 | 2 | 12 | 3 |
| last60d | 2026-07-13 | 0 | 11 | 49 | 2 | 19 | 15 |
| 90d | 2026-06-13 | 0 | 14 | 54 | 3 | 21 | 15 |
| last180d | 2026-03-15 | 1 | 41 | 64 | 7 | 34 | 54 |
| 360d | 2025-09-16 | 3 | 131 | 66 | 17 | 45 | 138 |
| last720d | 2024-09-21 | 7 | 351 | 66 | 66 | 81 | 358 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [multiple.intoto.jsonl](https://github.com/ossf/scorecard/releases/download/v5.5.0/multiple.intoto.jsonl) | 22.4 KiB | `other` |
| [scorecard_5.5.0_darwin_amd64.tar.gz](https://github.com/ossf/scorecard/releases/download/v5.5.0/scorecard_5.5.0_darwin_amd64.tar.gz) | 24.9 MiB | `native/darwin/x64` |
| [scorecard_5.5.0_darwin_arm64.tar.gz](https://github.com/ossf/scorecard/releases/download/v5.5.0/scorecard_5.5.0_darwin_arm64.tar.gz) | 23.3 MiB | `native/darwin/arm64` |
| [scorecard_5.5.0_linux_amd64.tar.gz](https://github.com/ossf/scorecard/releases/download/v5.5.0/scorecard_5.5.0_linux_amd64.tar.gz) | 25.2 MiB | `native/linux/x64` |
| [scorecard_5.5.0_linux_arm64.tar.gz](https://github.com/ossf/scorecard/releases/download/v5.5.0/scorecard_5.5.0_linux_arm64.tar.gz) | 23.1 MiB | `native/linux/arm64` |
| [scorecard_5.5.0_windows_amd64.tar.gz](https://github.com/ossf/scorecard/releases/download/v5.5.0/scorecard_5.5.0_windows_amd64.tar.gz) | 24.9 MiB | `native/win/x64` |
| [scorecard_5.5.0_windows_arm64.tar.gz](https://github.com/ossf/scorecard/releases/download/v5.5.0/scorecard_5.5.0_windows_arm64.tar.gz) | 22.4 MiB | `native/win/arm64` |
| [scorecard_checksums.txt](https://github.com/ossf/scorecard/releases/download/v5.5.0/scorecard_checksums.txt) | 612 B | `other` |

## Distribution status

Reported by **14** distros on [repology.org](https://repology.org/project/scorecard). **6** are ✅ on the latest upstream release, **7** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Homebrew | `5.5.0` | ✅ latest |
| Nix unstable | `5.5.0` | ✅ latest |

## Improve this data

Install metadata for scorecard lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `scorecard` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/scorecard.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260911.yml` · 2026-09-11T18:34:07Z._
