# Final Year Project Documentation

This repository documents the progress and results of the Final Year Project focused on retrieval-augmented generation (RAG), model evaluation, and comparative analysis of LLM and embedding-based approaches.

## Project Overview

The project includes:
- Initial dataset and knowledge base preparation for RAG
- Week 1 retrieval experiments and analysis
- Week 2 model comparison and evaluation results
- CSV outputs for retrieval metrics and LLM comparison

## Folder Structure

```text
Mega Project/
├── README.md
├── dataset/
│   └── Initial stage/
│       ├── cleaned_rag_document.txt
│       ├── phase 1 questions.docx
│       └── rag_knowledge_base.txt.txt
├── week 1/
│   ├── Week_1.ipynb
│   └── results/
│       ├── minilm_retrieval_results.csv
│       ├── mpnet_retrieval_results.csv
│       └── retrieval_summary.csv
├── week 2/
│   ├── Week_2.ipynb
│   └── result/
│       ├── week2_gemma_results.csv
│       ├── week2_llm_comparison.csv
│       ├── week2_phi_results.csv
│       └── week2_qwen_results.csv
└── venv/
    └── [Python virtual environment - excluded from git]
```

## Contents

### Dataset
- **Initial stage/**: Contains the project knowledge base and initial cleaned dataset for RAG experiments.
  - `cleaned_rag_document.txt`: Cleaned document used for retrieval and evaluation.
  - `rag_knowledge_base.txt.txt`: Core knowledge base used for retrieval tasks.
  - `phase 1 questions.docx`: Project question set for phase 1 evaluation.

### Week 1 Analysis
- **Week_1.ipynb**: Notebook for the first round of analysis and retrieval experiments.
- **results/**: Output files from the embedding and retrieval stage.
  - `minilm_retrieval_results.csv`: Retrieval results from MiniLM.
  - `mpnet_retrieval_results.csv`: Retrieval results from MPNet.
  - `retrieval_summary.csv`: Summary table comparing retrieval outputs.

### Week 2 Analysis
- **Week_2.ipynb**: Notebook for the second phase of model comparison and experimentation.
- **result/**: Result files from the week 2 evaluation.
  - `week2_gemma_results.csv`: Results for the Gemma model.
  - `week2_phi_results.csv`: Results for the Phi model.
  - `week2_qwen_results.csv`: Results for the Qwen model.
  - `week2_llm_comparison.csv`: Comparative summary across tested LLMs.

## Project Workflow

1. Prepare and clean the RAG dataset.
2. Build the knowledge base and retrieval pipeline.
3. Evaluate retrieval quality using different embedding models.
4. Compare multiple LLMs for answer quality and performance.
5. Document the findings and outputs in the project repository.

## Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook / JupyterLab
- Access to the project virtual environment

### Running the Notebooks

```bash
jupyter notebook "week 1/Week_1.ipynb"
jupyter notebook "week 2/Week_2.ipynb"
```

## Models and Evaluation

- **MiniLM**: Lightweight embedding-based retrieval model
- **MPNet**: Stronger sentence embedding model for retrieval tasks
- **Gemma**: LLM evaluated in week 2
- **Phi**: LLM evaluated in week 2
- **Qwen**: LLM evaluated in week 2

## Results Summary

The project contains both retrieval benchmarking results and LLM comparison outputs:
- Retrieval metrics and summaries for MiniLM and MPNet
- Comparative evaluation across Gemma, Phi, and Qwen
- CSV outputs for further analysis and reporting

## Repository Notes

- The `venv/` directory is intentionally excluded from git tracking to keep the repository clean and lightweight.
- Project files and experiment results are stored in `dataset/` and `week */` folders.

## License

This project is part of a Final Year academic project.

---

**Repository**: [FInal-Year-Project-Documentation](https://github.com/sahilc497/FInal-Year-Project-Documentation)

**Last Updated**: 2026-08-17
