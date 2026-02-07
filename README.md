# Pathogen–Host Mimicry: A Minimal Bioinformatics Pipeline

This repository implements a simple, reproducible pipeline to explore **peptide-level similarity between pathogen and human proteins**, motivated by hypotheses of immune cross-reactivity and molecular mimicry.

The goal is not to prove autoimmunity, but to demonstrate how computational biology can be used to **prioritize candidate mimicry events** for downstream experimental or modeling work.

---

## Biological Motivation

Adaptive immune responses recognize short peptide fragments. If pathogen-derived peptides resemble host peptides, immune activation may unintentionally target self-proteins.

This repository explores:
- sliding-window peptide generation
- simple similarity metrics
- transparent, interpretable outputs

---

## Repository Structure

- `data/` – raw and processed sequence data
- `notebooks/` – exploratory analysis and visualization
- `src/` – reusable Python functions
- `results/` – output tables and figures

---

## Status

🚧 Work in progress.  
Current focus: peptide extraction and similarity scoring.

---

## Requirements

See `requirements.txt`.
📌
