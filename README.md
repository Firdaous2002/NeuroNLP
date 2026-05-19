# NeuroNLP

This repository contains the code for the NLP2 Project C report, which compares the brain predictivity of sentence representations extracted from Qwen3-8B and Qwen3-Embedding-8B on the Pereira et al. fMRI dataset.

## Project structure

```text
NeuroNLP/
├── data/
│   └── participants/
│       └── M02/
│           ├── data_384sentences.mat
│           └── data_243sentences.mat
├── results/
│   ├── embeddings/
│   │   ├── Qwen/
│   │   │   ├── Experiment2_384/
│   │   │   └── Experiment3_243/
│   │   └── Qwen_Embedder/
│   │       ├── Experiment2_384/
│   │       └── Experiment3_243/
│   └── statistics/
├── voxel_encoding.ipynb
├── further_analysis.ipynb
└── notebook/
    └── inferential_statistics.ipynb
