# Fictional Regulatory Platform Modernization Case Study

This repository presents a domain-led modernization strategy for a fictional multi-tenant
regulatory platform. It focuses on product-line convergence, bounded contexts, governed
variability, incremental migration, platform engineering, and architecture decision rights.

All organizations, systems, customers, people, metrics, and timelines in this repository are
fictional. Quantitative values are synthetic planning targets or scale indicators created solely to
make the architectural reasoning testable; they are not historical results or claims about a real
organization.

## Canonical language

[CONTEXT.md](CONTEXT.md) defines the neutral domain language used throughout the case study,
including **Customer**, **Tenant**, **Jurisdiction**, **Shared Core**, and **Tracer Capability**.

## Case-study documents

| Document | Purpose |
|---|---|
| [Case-study premise](docs/01-case-study-premise.md) | Fictional constraints, synthetic outcomes, thesis, and architecture guardrails |
| [Decision and assumption log](docs/02-decision-log.md) | Architecture decisions, consequences, and validation hypotheses |
| [Case-study outline](docs/03-case-study-outline.md) | Public narrative and supporting architecture artifacts |
| [Domain architecture](docs/04-domain-architecture.md) | Context map, boundaries, contracts, orchestration, and consistency |
| [Bounded-context catalog](docs/05-context-catalog.md) | Context responsibilities, relationships, aggregates, and tracer scoring |
| [Customization governance](docs/06-customization-governance.md) | Core, configuration, extension, integration, and exception policy |
| [Current-state assessment](docs/07-current-state-assessment.md) | Evidence model, divergence measures, and assessment gates |
| [Shared-core migration roadmap](docs/08-migration-roadmap.md) | Incremental coexistence, tracer sequencing, and synthetic milestones |
| [Platform engineering foundations](docs/09-platform-engineering-foundations.md) | Golden paths, delivery controls, observability, and API governance |
| [Architecture operating model](docs/10-operating-model.md) | Decision rights, governance, team interactions, and scorecards |

## Publication boundary

The public case study is Markdown-only. Generated presentations, office documents, PDFs, previews,
temporary files, and local `output/` artifacts are outside the publication boundary and must not be
uploaded or committed.
