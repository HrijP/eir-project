# EiR — Small Domain-Aware Language Models for Rubrics-Based Assessment

## Structure
- src/        — training and inference scripts
- configs/    — hyperparameter and experiment configs
- data/       — corpus files (not committed to git)
- experiments/ — experiment registry and results
- notebooks/  — jupyter notebooks for analysis
- tests/      — pytest unit tests

## Corpus
- Statics domain: 14 ASEE papers, extracted via PyMuPDF
- Learning process domain: in progress

## Reproducibility
Every experiment records: corpus version, model checkpoint, hyperparameters, random seed, hardware, runtime.
