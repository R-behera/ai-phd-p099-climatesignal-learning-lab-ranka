# DataProvenance Model Bench: Data mining for Ranka-Aligned Research

A professor-outreach research proposal aligned with **Sanjay Ranka** at **University of Florida**.

## For Professor Outreach

This repo is intended to support an honest outreach email. It contains a concrete proposal for what value you can add, but it does **not** yet contain completed experiments or results.

Start here:

- `outreach/value_add_packet.md` - professor-specific contribution plan.
- `outreach/email_draft.md` - short mail draft you can personalize before sending.
- `docs/one_page_project_plan.md` - one-page project summary.
- `PROJECT_STATUS.md` - clear statement of what exists and what does not exist yet.

## Research Question

How can a focused, reproducible artifact around **Data mining** create useful research infrastructure for a lab working on **Data mining, HPC, machine learning, big data analytics**?

## Advisor Fit

- **Professor:** Sanjay Ranka
- **University:** University of Florida
- **Program:** CISE PhD (CS)
- **CSV research area:** Data mining, HPC, machine learning, big data analytics
- **Representative paper:** Elements of Artificial Neural Networks (textbook); 1997; MIT Press
- **Scholar link:** https://scholar.google.com/scholar?q=Elements+of+Artificial+Neural+Networks+%28textbook%29

## Proposed Research-Grade Deliverable

Build **an auditable ML decision-support pipeline with provenance, uncertainty, and failure analysis** with:

- Dataset card and validation checks.
- Baseline and proposed model comparison.
- Calibration, subgroup, and shift analysis.
- Auditor-facing report with limitations and next experiments.

## Quick Start

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m pytest
```

## Repository Map

- `outreach/value_add_packet.md` - value-add plan for this professor.
- `outreach/email_draft.md` - email draft; personalize before sending.
- `docs/research_brief.md` - project hypothesis, novelty, methods, and evaluation plan.
- `docs/one_page_project_plan.md` - one-page project summary.
- `docs/experiment_plan.md` - baseline, ablation, and reporting protocol.
- `configs/baseline.yaml` - first experiment configuration placeholder.
- `reproducibility/commands.md` - exact commands and environment notes.
- `data/source_programs.csv` - original CSV for traceability.

## Status

Proposal scaffold only. Before external use, verify the professor's current lab page and make a selected repo public or shareable.
