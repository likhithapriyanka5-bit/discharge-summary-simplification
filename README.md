# Discharge Summary Simplification for Elderly Patients

A three-stage NLP pipeline that simplifies clinical discharge summaries for elderly patients while preserving important medical facts.

## Overview
- Extracted drugs and diseases using a clinical NER model (MedSpaCy)
- Used Llama 3.3 with structured prompts to rewrite the notes in simple language
- Evaluated readability and factual accuracy

## Tech Stack
- Python
- MedSpaCy
- Llama 3.3
- MIMIC-III

## Results
Simplified notes reached around 7th-grade reading level while keeping most important medical facts accurate.

## Note
This was a group project completed as part of the NLP for Social Good course at Leiden University.
