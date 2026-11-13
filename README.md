# Technical Documentation Portfolio

[English](README.md) | [Русский](README.ru.md)

A public portfolio dashboard for real technical writing and documentation engineering projects.

**Live dashboard:** https://github-profile-dashboard-vite.vercel.app/  
**GitHub profile:** https://github.com/ekatmoz88-alt  


## Purpose

The dashboard presents selected documentation case studies across API documentation, enterprise information systems, desktop applications, database architecture and source-based technical analysis.

The dashboard links to public documentation sites, repositories and technical case studies. Related materials for the Territory system and its associated components are presented as one connected documentation project.

## Featured work

The dashboard currently presents **6 curated project cards**. This is intentionally a selected-work section, not a one-card-per-repository list. The live **All public repositories** index retrieves the public repository inventory from GitHub.

- [Orders API Documentation](https://github.com/ekatmoz88-alt/api-docs-portfolio-v2) — REST API reference and OpenAPI 3.1, with Docs-as-Code validation.
- [ППО «Территория» — unified technical documentation](https://github.com/ekatmoz88-alt/territory-descriptor-unified-public) — separate portfolio track; do not treat it as the same product as АРМ «Дешифратор». The project-level role of ППО «Территория» as an external data context is described only where supported by the historical Deshifrator specification.
- [АРМ «Дешифратор» — program description and documentation](https://ekatmoz88-alt.github.io/deshifrator-docs-public/) · [source-based documentation](https://github.com/ekatmoz88-alt/deshifrator-docs-public) · [project specification](https://github.com/ekatmoz88-alt/descriptor-arm-spec) — one historical desktop application project. «Дискриптор» / “Descriptor” is an earlier name for the same project, not a separate product. The two repositories have complementary scopes: the first reviews selected C# source excerpts; the second records the project-level specification for ПОСС, ПОМС and ПОШ ВБД. Requirements and implementation evidence are kept distinct.
- [GLOBAL11 — Oracle Data Platform](https://github.com/ekatmoz88-alt/global11-demo-data-platform) — real Oracle Global 11g platform deployed and operated on an office server; relational model, data dictionary, schema changes and OLAP design documentation.
- [Cobalt UI Navigation](https://github.com/ekatmoz88-alt/cobalt-ui-navigation-docs) — source-based C++ component documentation.
- [Fintech Operations Documentation](https://ekatmoz88-alt.github.io/fintech-docs-demo/) — anonymized documentation of a real crypto-onramp operator-console project, including workflows, data classification and audit logging.
- [Technical Writing Workflows](https://ekatmoz88-alt.github.io/technical-writing-workflows/) — automated OpenAPI, Markdown and link-quality checks.
- [ADP201P4 Hardware Documentation](https://ekatmoz88-alt.github.io/adp201p4-hardware-spec/) — source-based signal-processing module architecture and interface documentation.

## Dashboard behavior

- Public GitHub profile information and repository activity are retrieved from the GitHub REST API.
- Featured project descriptions and their links are curated in the dashboard source.
- The C# / SQLite review documents the DbStationary data-access layer within the Deshifrator materials. The dashboard also includes the separate GLOBAL11 demo data platform.
- Public API rate limits may temporarily affect live profile and activity data.

## Technology

- React 18
- Vite 6
- JavaScript
- GitHub REST API
- GitHub Actions
- Vercel and GitHub Pages

## Run locally

Requirements: Node.js 24 and npm.

```bash
npm ci
npm run dev
```

Create a production build and preview it locally:

```bash
npm run build
npm run preview
```

## Deployment

The live dashboard is deployed to Vercel at the domain root: https://github-profile-dashboard-vite.vercel.app/. The repository does not currently contain a GitHub Pages deployment workflow for the Vite application. The other portfolio projects keep their own independent GitHub Pages sites.

## Featured architecture documentation

- [Data exchange and administration — EN](https://github.com/ekatmoz88-alt/territory-descriptor-unified-public/blob/main/materials/architecture/data-exchange-and-administration.en.md)
- [Обмен данными и администрирование — RU](https://github.com/ekatmoz88-alt/territory-descriptor-unified-public/blob/main/materials/architecture/data-exchange-and-administration.ru.md)

## Evidence and scope

All featured cards refer to real projects and workstreams; system projects were deployed in their respective server environments. The dashboard identifies the author's documentation, analysis and source-review contribution without implying authorship of the underlying software where that was not the role. Historical deployment facts are retained; public descriptions are anonymized where required, and technical findings are tied to project materials and inspected source evidence.


## Tags

`portfolio-dashboard` · `react` · `vite` · `github-api` · `technical-writing` · `repository-audit` · `en-ru`
