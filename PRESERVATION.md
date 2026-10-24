# Preservation record

## Origin and attribution

- Original project: https://github.com/blackbearreloaded/ps5-opengl
- Original project author: BlackBearReloaded; all other component and contributor notices are retained.
- Preserved by: JMUtechnologies.
- Preservation date: 2026-10-24.
- Original version: 1.0.2.
- Source snapshot and runtime source commit: `a519561626933257213d64a4a8bd5e02b55dceb2`.

This is a preservation repository, not a claim of original authorship or an official continuation.

## Workstation copy and exact release recovery

The workstation retained an installed SDK, with 66 files including headers, compiled libraries, build integration, licenses, and third-party notices. It did not retain the complete original source repository or the release's source companions. The original installer recorded the expected full release archive and SDK manifest SHA-256 values.

The complete original archive was recovered from this surviving mirror:

https://github.com/LedyBacer/ps5-opengl/releases/download/v1.0.2/ps5-opengl-sdk-1.0.2.tar.gz

Its SHA-256 matches the value pinned in the workstation installer:

```text
30d8e51dd062739b629346102be5932728ba714bc50b1bdcdf08306c8843d9a4  ps5-opengl-sdk-1.0.2.tar.gz
```

Every one of the 66 locally installed files matched the corresponding file inside that release byte for byte. All 45 SDK manifest entries passed their checksums. The SDK manifest itself has SHA-256:

```text
0d432edc9d648d6e0cccb4d5eb3db8484f10ba4b075b5ccf23edda3251b66360
```

The [preserved release](https://github.com/JMUtechnologies/ps5-opengl/releases/tag/v1.0.2) provides the original archive unchanged, including all 10 source archives, original provenance, notices, and checksums. Its 154 internal checksum entries and every source archive checksum were verified. This preserves the workstation's exact SDK bytes together with their original source companions.

## Repository source and history

The repository contains all 626 files from `sources/ps5-opengl.tar` inside the original release. Every file's Git blob hash and mode was checked against commit `a519561626933257213d64a4a8bd5e02b55dceb2`, also available from the surviving `LedyBacer/ps5-opengl` mirror. The source snapshot was recovered from that release, rather than found as a local source checkout. Earlier Git history, issues, pull requests, and unrelated release versions are not imported.

Only preservation documentation and workflow locations differ from the recovered source:

- A preservation notice precedes the original README; the original content remains below its separator.
- This preservation record was added.
- Original GitHub Actions workflows remain unchanged under `.github/preserved-workflows/`. They are inactive. Review their destinations and dependencies before enabling them.

Original source code, patches, assets, license texts, and component notices are unchanged. The SDK archive is a release asset rather than a Git source file. No local credentials, personal paths, build caches, or uncommitted workstation changes were added.

## Licenses and validation limits

The original [LICENSE](LICENSE), [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md), and component licenses under `LICENSES/` remain included. Their terms continue to apply to the project and each dependency. The complete SDK release includes the project's matching source, dependency source archives, and original redistribution notices.

File integrity, source identity, and available Python/shell syntax were checked for this import. The SDK was not rebuilt or executed, and no PS5 hardware test was performed. Original release provenance labels these exact SDK binaries **host-built and host-checked; not console-validated**. Historical reports in the source documentation do not establish new hardware validation for this preserved binary. Original dependency links and pins are retained; preservation does not guarantee their continued availability.
