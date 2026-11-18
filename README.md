<!-- markdownlint-disable MD013 MD033 MD036 MD041 -->
<!-- A centred header needs inline HTML, a banner image, a bold tagline and
     badge lines past 80 columns, so those four rules are off for this file.
     Same directive style as profile/README.md. The prose below still wraps at
     80. -->
<!-- SPDX-FileCopyrightText: Tekmora contributors -->
<!-- SPDX-License-Identifier: EUPL-1.2 -->
<div align="center">

  <img src="profile/tekmora-readme-banner.svg" alt="Tekmora — open tools for building software with AI agents, evidence before compute" height="120" />

  <!-- README-STANDARD badge block: one group, fixed order (VMAFx docs/README-STANDARD.md) -->
  <!-- 4 standards -->
  [![HISS-21](https://img.shields.io/badge/Standards-HISS--21-06b6d4?style=for-the-badge&logo=nasa&labelColor=111a35)](https://github.com/tekmora/.github/blob/main/AGENTS.md)
  [![Conventional Commits](https://img.shields.io/badge/Commits-Conventional-8b5cf6?style=for-the-badge&logo=conventionalcommits&logoColor=white&labelColor=111a35)](https://www.conventionalcommits.org/en/v1.0.0/)
  <!-- 5 licence -->
  [![License](https://img.shields.io/badge/License-EUPL--1.2-3b82f6?style=for-the-badge&labelColor=111a35)](https://github.com/tekmora/.github/blob/main/LICENSE)
  <!-- 6 support -->
  [![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub-8b5cf6?style=for-the-badge&logo=githubsponsors&logoColor=white&labelColor=111a35)](https://github.com/sponsors/lusoris)
  [![Ko-fi](https://img.shields.io/badge/Support-Ko--fi-8b5cf6?style=for-the-badge&logo=kofi&logoColor=white&labelColor=111a35)](https://ko-fi.com/lusoris)

  **Organisation profile and default community files for Tekmora**

  *The page shown on github.com/tekmora and the files every Tekmora repository inherits*

</div>

This repository holds the Tekmora organisation profile and the community files
that GitHub applies to every repository in the organisation that has none of
its own.

The name Tekmora comes from Greek *tekmor* (Homeric *tekmor*): a set goal, and
the sign that shows the way to it. Said *TEK-mo-ra*. The profile explains it in
full.

## At a glance

| Path | What it is |
| --- | --- |
| [`profile/README.md`](profile/README.md) | The organisation profile shown on the organisation page. |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | The default Code of Conduct for every repository without its own. |
| [`.github/FUNDING.yml`](.github/FUNDING.yml) | The default sponsor button for every repository without its own. |
| [`LICENSE`](LICENSE) | EUPL-1.2, the licence of this repository. |

## Contribute

Changes come as pull requests against `main`. Questions about a project go to
that project's Discussions; the profile links each one.

## Support

Sponsor the work on [GitHub Sponsors](https://github.com/sponsors/lusoris) or
[Ko-fi](https://ko-fi.com/lusoris), any amount; no support or priority is sold.

## Upstream and licence

Licence: EUPL-1.2 ([`LICENSE`](LICENSE)).

## Standards and governance

<!-- praetor:readme-governance:start -->
Praetor manages this repository's declared governance policy. This managed
block records adoption state; it is not a verification certificate.

**Verification**: `make verify-all` runs the repository's configured
verification cascade.

**HISS Audit**: `praetorctl audit` enforces policy, generated-surface
integrity, and the debt ratchet.

**Context Sync**: `praetorctl compile-context --verify` verifies every
generated agent context against `AGENTS.md`.

**Debt Baseline**: `.standards-baseline.json` anchors the debt ratchet at
0 recorded infractions; audit forbids growth.
<!-- praetor:readme-governance:end -->
