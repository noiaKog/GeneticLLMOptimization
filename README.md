# Genetic LLM Optimization

## Project Purpose

This project explores how different tokenization methods impact the performance of language models (LLMs) in identifying genetic sequences—specifically promoter regions (TATA and non-TATA).

By comparing three tokenization strategies—BPE, WordPiece, and k-mer—across datasets from various organisms, the project aims to answer:

* Does the choice of tokenization affect model accuracy depending on the organism?
* Is there a connection between genetic sequence structure and the effectiveness of certain token types?
* Can model performance improve by tailoring tokenization methods to the unique characteristics of each organism?

Used XAI tools (e.g., SHAP) to interpret predictions, visualize attention, and discover meaningful genetic motifs.

Additionally, the project investigates an evolution-aware approach, where organisms are grouped by genetic proximity to humans. The model is trained progressively to examine whether evolutionary relationships help enhance generalization.

## Files
1. Data:
   * raw files
   * positive data combination
   * train - test split for both methods 
   * negative data creation for both methods
3. notebooks:
    * BPE notebook - implementation of masking and fine tune for both methods
    * KMER notebook - implementation of masking and fine tune for both methods
    * WPC genome - notebook - implementation of masking and fine tune for negative metod genome
    * WPC replacement - notebook - implementation of masking and fine tune for negative method replacement
