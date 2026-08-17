# Nouraldin Farge — Software Engineer

I build user-facing products with **React and TypeScript**, then carry them through data design, testing, documentation, and release. My strongest differentiator is turning complex or sensitive workflows into dependable local-first software with clear product boundaries.

I’m based in Chicago and open to software engineering roles across frontend, full-stack product development, and desktop applications.

[Portfolio](https://nouraldinfarge.github.io) · [Résumé](https://nouraldinfarge.github.io/Nouraldin-Farge-Resume.pdf) · [LinkedIn](https://www.linkedin.com/in/nouraldin-farge/)

## Projects

### [DrawScope](https://github.com/NouraldinFarge/drawscope) · v0.6.5

A React/Tauri research workbench that makes data lineage, methodology, and product limits visible instead of presenting historical lottery patterns as predictions.

- 41,598 deduplicated draws across six games
- 250 leakage-resistant walk-forward trials with a 60/40 discovery–confirmation split
- Reproducible SQLite archive, cross-language contract tests, checksum, SBOM, and provenance

[Repository](https://github.com/NouraldinFarge/drawscope) · [Windows release](https://github.com/NouraldinFarge/drawscope/releases/tag/v0.6.5) · [Methodology](https://github.com/NouraldinFarge/drawscope/blob/main/docs/METHODOLOGY.md)

### [GameVault](https://github.com/NouraldinFarge/gamevault) · v0.3.5

A portable React/Tauri game library and launcher with a review-gated archive intake pipeline for user-owned files.

- Blocks traversal, unsafe Windows paths, links, reparse entries, and decompression abuse
- Uses a relative-path SQLite catalog, launch history, backups, and rollback
- Ships with focused Rust and React/Vitest coverage, checksum, SBOM, and provenance

[Repository](https://github.com/NouraldinFarge/gamevault) · [Windows release](https://github.com/NouraldinFarge/gamevault/releases/tag/v0.3.5) · [Safety model](https://github.com/NouraldinFarge/gamevault#safety-model)

### [Day-Trading Teacher](https://github.com/NouraldinFarge/day-trading-teacher) · v0.36.0 public release

A 13-lesson local-first learning environment that connects decision planning, historical replay, paper practice, journaling, reflection, and spaced review.

- Implements deterministic decimal risk and expectancy calculations in Rust
- Validates lesson imports with Zod and preserves provenance in Fidelity trade-history review
- Intentionally excludes brokerage access, live signals, investment advice, and order execution

[Repository](https://github.com/NouraldinFarge/day-trading-teacher) · [Windows release](https://github.com/NouraldinFarge/day-trading-teacher/releases/tag/v0.36.0) · [Project tour](https://github.com/NouraldinFarge/day-trading-teacher#five-minute-project-tour)

### [Research Studio](https://github.com/NouraldinFarge/research-studio-case-study) · private build v0.1.0-alpha.24

A guarded Electron/React workflow for bilingual catalog enrichment. It keeps source data read-only, treats model output as untrusted, requires human approval, and exports only versioned approved metadata.

- Validated against 31,521 series and 2,242,170 episodes without changing the source database hash
- Uses isolated working copies, schema and evidence gates, batches capped at five, and recoverable exports
- Documented in a public, source-free case-study snapshot published August 15, 2026

[Case study](https://github.com/NouraldinFarge/research-studio-case-study) · [Verification evidence](https://github.com/NouraldinFarge/research-studio-case-study/blob/main/docs/verification-evidence.md) · [Threat model](https://github.com/NouraldinFarge/research-studio-case-study/blob/main/docs/threat-model.md)

The implementation, builds, catalog, browser material, and private diagnostics are not public. The case-study repository contains only redistribution-safe documentation and synthetic examples.

## How I engineer products

- Start with the user workflow, the decision the product supports, and the failure state it must explain.
- Keep filesystem, database, process, browser, and model authority behind explicit boundaries.
- Validate imported data with schemas, provenance, deterministic rules, and human review.
- Test behavior across UI, domain logic, persistence, and release paths.
- Publish evidence with product claims: documentation, automated checks, checksums, SBOMs, and provenance where applicable.

## AI-assisted development and accountability

AI agents assist with research, implementation, test generation, and iteration. I remain responsible for product direction, architecture, technical review, verification, safety and licensing boundaries, data-source decisions, published claims, and final release approval. Agent output is treated as untrusted until it passes repository checks and human review.

## Current stack

- **Product and frontend:** React, TypeScript, JavaScript, HTML/CSS, Vite
- **Application and backend:** Rust, Tauri, Electron, Node.js, Express, Python
- **Data and validation:** SQLite, SQL, JSON Schema, Zod
- **Quality and delivery:** Vitest, Playwright, pytest, Cargo/Clippy, GitHub Actions, CodeQL, SBOMs, checksums, provenance

## Contact

The best public contact is [LinkedIn](https://www.linkedin.com/in/nouraldin-farge/). Project bugs and proposals belong in the relevant repository; suspected vulnerabilities should use private vulnerability reporting.
