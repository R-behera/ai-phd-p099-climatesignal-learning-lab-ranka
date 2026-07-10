# Unique Prototype Algorithm

## Algorithm

**RankaProvenanceDataMiningExplainAgent** (`P099-Ranka-DataMining`)

## Professor Alignment

- Professor: Sanjay Ranka
- Research area: Data mining, HPC, machine learning, big data analytics
- Focus terms: Data mining, HPC, big data analytics

## Core Mechanism

This prototype prioritizes decision-support failures with calibration and subgroup reliability risk.

## Decision Rule

Rank seed cases by ml-specific priority score with Ranka-aligned focus term 'Data mining'.

## What The Code Adds

- A unique algorithm spec in `src/proposed_method.py`.
- A scoring function for the repo's `ml` data schema.
- A ranked list of cases that should be reviewed, repaired, reproduced, or expanded first.
- Integration into `src/value_add.py`, so demo output includes the proposed method.

## Honest Status

This is a runnable algorithmic prototype. It is not a validated contribution to Sanjay Ranka's published work until the seed data is replaced with real public/lab-relevant data and the resulting claims are evaluated.

## Run

```bash
python src/proposed_method.py
python src/value_add.py --write-report reports/demo_results.json
python -m unittest discover -s tests
```
