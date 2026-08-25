# Nouraldin Farge — Software Engineer

I build user-facing products with **React and TypeScript**, then carry them through data design, testing, documentation, and release. I focus on dependable local-first software where security boundaries, evidence, and failure states matter.

I’m based in Chicago and open to software engineering roles across frontend, full-stack product development, and desktop applications.

[Portfolio](https://nouraldinfarge.github.io) · [Résumé](https://nouraldinfarge.github.io/Nouraldin-Farge-Resume.pdf) · [LinkedIn](https://www.linkedin.com/in/nouraldin-farge/) · [Portfolio source](https://github.com/NouraldinFarge/portfolio-source)

## Projects

- **[DrawScope](https://github.com/NouraldinFarge/drawscope) · v0.6.5** — React/Tauri research workbench for auditable lottery archives and honest historical pattern testing. Its reproducible SQLite dataset contains 41,598 deduplicated draws across six games, and its methodology uses leakage-resistant walk-forward trials instead of prediction claims. [Release](https://github.com/NouraldinFarge/drawscope/releases/tag/v0.6.5) · [Methodology](https://github.com/NouraldinFarge/drawscope/blob/main/docs/METHODOLOGY.md)

- **[GameVault](https://github.com/NouraldinFarge/gamevault) · v0.3.5** — Portable React/Tauri game library for user-owned files. Its review-gated archive pipeline blocks traversal, unsafe Windows paths, links, reparse entries, and decompression abuse before extraction. [Release](https://github.com/NouraldinFarge/gamevault/releases/tag/v0.3.5) · [Safety model](https://github.com/NouraldinFarge/gamevault#safety-model)

- **[Day-Trading Teacher](https://github.com/NouraldinFarge/day-trading-teacher) · v0.36.0** — Thirteen-lesson local-first environment for planning, historical replay, paper practice, journaling, and review. Rust provides deterministic decimal calculations; the product intentionally excludes brokerage access, live signals, and order execution. [Release](https://github.com/NouraldinFarge/day-trading-teacher/releases/tag/v0.36.0) · [Project tour](https://github.com/NouraldinFarge/day-trading-teacher#five-minute-project-tour)

- **[Research Studio](https://github.com/NouraldinFarge/research-studio-case-study) · source-free case study** — Guarded Electron/React workflow for bilingual catalog enrichment, validated against 31,521 series and 2,242,170 episodes without changing the source database hash. Model output stays untrusted until schema, evidence, and human-review gates pass. [Evidence](https://github.com/NouraldinFarge/research-studio-case-study/blob/main/docs/verification-evidence.md) · [Threat model](https://github.com/NouraldinFarge/research-studio-case-study/blob/main/docs/threat-model.md)

## Active public-source work

- **[Reader](https://github.com/NouraldinFarge/Reader)** — Local-first Windows reading-library alpha for EPUB, PDF, text, and authorized audio.
- **[Media Scout](https://github.com/NouraldinFarge/media-scout-downloader)** — Permission-scoped Manifest V3 extension for media discovery and authorized downloads.
- **[SiteWipe](https://github.com/NouraldinFarge/SiteWipe)** — Safety-engineering prerelease for reviewed, target-scoped browser-data cleanup; its release gates remain open.

These repositories are available for code review, but they are not supported public binary or extension-store releases. The [portfolio](https://nouraldinfarge.github.io/#active-source) keeps them visually separate from the shipped projects and case study above.

## How I work

- Start with the user workflow, the decision the product supports, and the failure state it must explain.
- Keep filesystem, database, process, browser, and model authority behind explicit boundaries.
- Validate imported data with schemas, provenance, deterministic rules, and human review.
- Test across UI, domain logic, persistence, security boundaries, and release paths.
- Publish evidence with product claims: documentation, checks, checksums, SBOMs, and provenance where applicable.

## AI-assisted development and accountability

AI agents assist with research, implementation, test generation, and iteration across these projects. I remain responsible for product direction, architecture, technical review, verification, safety and licensing boundaries, data-source decisions, published claims, and final release approval. Agent output is treated as untrusted until it passes repository checks and human review.

## Stack and contact

Core stack: React · TypeScript · JavaScript · Rust · Tauri · Electron · Node.js · Python · SQLite · Vitest · Playwright · pytest · GitHub Actions · CodeQL

The best public contact is [LinkedIn](https://www.linkedin.com/in/nouraldin-farge/). Project bugs and proposals belong in the relevant repository; suspected vulnerabilities should use private vulnerability reporting.
