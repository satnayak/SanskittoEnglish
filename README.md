# Sanskrit-to-English Neural Machine Translation

A custom Neural Machine Translation system for translating Sanskrit
sentences into English.

## Overview

This project implements an attention-based Sequence-to-Sequence model
for Sanskrit-to-English translation.

## Architecture

- Unicode-aware preprocessing
- Sanskrit and English vocabularies
- Bidirectional GRU Encoder
- Bahdanau Additive Attention
- GRU Decoder
- Teacher Forcing
- Gradient Clipping
- Early Stopping
- Greedy Decoding

## Dataset

The dataset contains aligned Sanskrit-English sentence pairs:

- Training: 10,000 pairs
- Development: 1,000 pairs
- Test: 1,000 pairs

Sentence pairs are aligned using `Source_id`.

The dataset files are not included in this repository unless
redistribution is explicitly permitted.

## Evaluation

The model is evaluated using:

- BLEU
- BERTScore
- Qualitative translation analysis
- Attention visualization
- Error analysis

## Repository Structure

```text
notebooks/   Jupyter notebook implementation
report/      Final experimental report
data/        Dataset instructions
