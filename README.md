# Synthetic Text Data Generation with Quantized LLMs

This repository contains the code and experiments developed for a TFG focused on the generation of synthetic textual data using quantized Large Language Models (LLMs).

## Objective
The main objective of this project is to evaluate whether quantized LLMs can generate high-quality synthetic text in resource-constrained environments.

## Scope
- Comparison of different prompting techniques (zero-shot, few-shot, etc.)
- Evaluation of text quality, semantic alignment, and diversity
- Analysis of memory and computational constraints

## Repository Structure
- `notebooks/`: Jupyter notebooks corresponding to each phase of the methodology:
  - Phase 1: Quantized LLM selection
  - Phase 2: Synthetic dataset generation
  - Phase 3: Dataset evaluation
- `data/`: Synthetic datasets generated during the experiments
- `results/`: Evaluation results and metrics derived from the generated datasets

### Notebooks Overview

- `01_model_selection.ipynb`: Selection and analysis of quantized LLMs under hardware constraints.
- `02_dataset_generation.ipynb`: Generation of the synthetic text dataset using the selected model.
- `03_dataset_evaluation.ipynb`: Evaluation of the generated dataset using qualitative and quantitative metrics.

### Dataset Description

The generated synthetic dataset is provided in Excel format and contains the outputs produced during Phase 2 of the project. Each row corresponds to a generated text instance along with its associated attributes used during evaluation.

### Results Overview

This folder contains the results obtained during Phase 3 of the project.

The evaluation focuses on the quality of the generated synthetic dataset, including qualitative analysis and quantitative metrics derived from the experimental setup.

## Technologies
- Python
- Quantized LLMs
- Prompt Engineering
- NLP Evaluation Metrics

## Author
Laura Santamaría Báez

