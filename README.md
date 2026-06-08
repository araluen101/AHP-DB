# AHP DB: A Reference Database of the Human Aqueous Humor Proteome

The first publicly accessible reference of the complete human aqueous humor proteome,
queryable and stratifiable by clinical and biochemical parameters. Published in
*Database* (Oxford) and indexed in PubMed.

[![Paper](https://img.shields.io/badge/Database%20(Oxford)-baae001-blue)](https://doi.org/10.1093/database/baae001)

## The problem

The aqueous humor, the fluid inside the eye, is one of the most diagnostically underused
biological samples in ophthalmology. Dozens of labs had published proteomes and protein
lists derived from it, but none of that data was consolidated anywhere usable. To answer a
question like "which aqueous humor proteins change with age, or differ by race, or are
elevated in glaucoma," a researcher had to dig through the primary literature, reconcile
results from different mass-spectrometry platforms and incompatible annotation conventions,
and rebuild the table from scratch. Every group repeated the same compilation work in
private.

The bottleneck was not experimental. It was structural. The data already existed; what was
missing was shared infrastructure to make it usable across labs. AHP DB is that
infrastructure.

## What it provides

- A normalized, consolidated reference of proteins reported in the human aqueous humor.
- Stratification by **age, sex, race, disease state, and biochemical parameters** in a
  single query, rather than manual cross-referencing across papers.
- A consistent annotation layer over sources that originally used different platforms and
  naming conventions.

## My contributions

This is a collaborative, peer-reviewed project with the full author list below. My role:

- Designed the curation protocol used to pull and normalize proteins from the published
  aqueous humor literature.
- Reconciled results across differing mass-spectrometry platforms and annotation standards
  into a single consistent schema.
- Designed the database schema that supports stratified queries by clinical and biochemical
  parameters.
- Wrote the analysis code in R (RStudio) behind the curation and figures.

## Access

- **Paper:** https://doi.org/10.1093/database/baae001
- **Live database:** [FILL IN: the URL where AHP DB is hosted, if a public interface exists]

## Citation

Lee TJ, Goyal A, Jones G, Glass J, Doshi V, Bollinger K, Ulrich L, Ahmed S, Kodeboyina SK,
Estes A, Toteberg-Harms M, Zhi W, Sharma S, Sharma A. AHP DB: a reference database of
proteins in the human aqueous humor. *Database* (Oxford). 2024; 2024:baae001.
https://doi.org/10.1093/database/baae001

## About this repository

This repo is a project showcase and pointer to the published resource. The canonical paper
and data live with the publication. If you add code here, include only scripts you have the
right to share, and coordinate with the coauthors before republishing any underlying
datasets.

<!--
EDIT BEFORE PUBLISHING:
1. Fill in the live database URL above, or remove that line if there is no public interface.
2. If you upload sanitized R scripts or the curation pipeline, add a "Repository contents"
   section listing the files, and confirm with coauthors that sharing them is fine.
3. Optionally add a couple of example queries or a screenshot of the database to make the
   repo concrete for a reviewer skimming it.
-->
