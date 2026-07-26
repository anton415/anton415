# Anton Serdyuchenko

I build local-first products where requirements, architecture, tests, and operational safety are explicit. My current work combines Python backend engineering, financial domain modeling, and controlled AI-assisted development.

## Active project: Personal Finance Tracker

**Personal Finance Tracker** is a local-first FastAPI application replacing an Excel-based workflow for investments and personal finances with structured data, testable calculations, and privacy-safe AI access.

> **Current stage:** v0.2 development  
> **Current focus:** Ownership Recovery and reliability  
> **Next increment:** tested SQLite backup and restore

### What is already implemented

- Excel-to-SQLite migration validated with synthetic fixtures
- portfolio positions, allocation, target deviation, and budget-aware buy plans
- per-account portfolio views and editable target allocations
- manual buy transactions and on-demand MOEX price updates
- read-only portfolio data-quality checks
- versioned JSON and Markdown exports for AI-assisted analysis
- automated tests for financial calculations, migration, and data integrity

### Engineering direction

- local-first and single-user by default
- deterministic financial facts separated from assumptions and manual or AI assessments
- explicit requirements, ADRs, migrations, and testable invariants
- gradual path toward funds, currencies, deposits, P/L and XIRR, FIRE planning, versioned AI access, and a local MCP server with human approval
- no real financial data or secrets in Git

### Stack

`Python` · `FastAPI` · `SQLAlchemy 2.0` · `Alembic` · `SQLite` · `pytest` · `Ruff` · server-rendered HTML

The source repository is currently private while I complete a dedicated privacy, security, Git-history, documentation, and licensing audit. Public case studies and proof-of-work artifacts will be added progressively.

## Current engineering interests

AI Software Engineering · backend architecture · financial domain modeling · testing and reliability · local-first systems · safe AI integration · spec-driven development · developer tooling

## Working principle

AI should strengthen engineering judgment through explicit requirements, reviewable artifacts, tests, and controlled workflows—not replace understanding.

---

### Кратко по-русски

Сейчас мой единственный активный продуктовый проект — **Personal Finance Tracker**: local-first система для инвестиций, личных финансов и движения к FIRE. Проект одновременно является используемым продуктом, портфолио-проектом и практической средой для развития.
