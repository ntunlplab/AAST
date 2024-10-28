# AAST Dataset - Academic Article Survey Tables

## Overview
Welcome to the AAST dataset repository! This dataset focuses on Academic Article Survey Tables and has been meticulously curated through processes involving the arXiv and Semantic Scholar APIs. For a detailed overview, please refer to our comprehensive AAST_Dataset_Documentation.pdf.

This dataset is part of our paper "Survey Table Generation from Academic Articles" accepted at WI-IAT 2024.

## License
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## Data Sources
- Tables, metadata and factual information from arXiv papers
- S2ORC through Semantic Scholar Public API
- GPT-generated summaries (where indicated)

## Files in this Repository
### AAST.json
- Located in: AAST.7z archive
- Content: Primary dataset file containing:
  - AAST survey paper section data
  - Reference details
  - Paper abstracts
  - GPT-4 generated fields for additional context

### corpus_id_introduction.json
- Content: Introduction sections extracted from S2ORC database
- Features:
  - Original text
  - GPT-3.5 compressed versions

### corpus_id_ori_and_sc_other.json
- Located in: corpus_id_ori_and_sc_other.zip archive
- Content: Additional paper sections from S2ORC database
  - Excludes images and tables
  - Includes both original and GPT-3.5 compressed versions
