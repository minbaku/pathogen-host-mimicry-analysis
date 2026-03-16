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

⚠️ Preliminary exploration — superseded by full pipeline

This repository represents an early exploratory version of peptide 
similarity analysis. The complete, validated pipeline with structural 
confirmation across 32 organisms and ML classification is available at:

👉 molecular-mimicry-RA-pipeline

---

## Requirements

See requirements.txt.
📌
---

## Results and Conclusions:

- 👉 We can conclude from the outcomes of the code that the exact matches between the Pathogen peptide Sequence (_Campylobacter jejuni_ - Sialic Acid Biosynthesis Protein[NeuA]) and Human Sequence (_Homo sapiens_ - Thyroglobulin Precursor Protein[TG]) are none, since the result for matches came out to be 0.
- 👉 BLAST results and Literature review still give evidence of immunogenicity. Therefore, the result shows that similarity doesn't depend on exact matches of sequence but also on similarity of sequences with the presence of Gaps and Substitutes.
- 👉 The Results also demonstrate the significance of Twilight zone Sequences which are sequences that present sequence identity of 30%-70%. This observation is very important because it shows the significance of structural similarity in immunogenicity and thus, molecular mimmicry of certain proteins.
