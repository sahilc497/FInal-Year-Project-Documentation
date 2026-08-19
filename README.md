# Final Year Project Documentation

This repository documents a final-year project on retrieval-augmented generation (RAG), retrieval evaluation, and comparison of large language models.

## Project Contents

```text
README.md
dataset/
  Initial stage/
    cleaned_rag_document.txt
    phase 1 questions.docx
    rag_knowledge_base.txt.txt
week 1/
  Week_1.ipynb
  results/
    minilm_retrieval_results.csv
    mpnet_retrieval_results.csv
    retrieval_summary.csv
week 2/
  Week_2.ipynb
  result/
    week2_gemma_results.csv
    week2_llm_comparison.csv
    week2_phi_results.csv
    week2_qwen_results.csv
week 3/
  Week_3.ipynb
  result/
    week3_hitk_evaluation.csv
    week3_hitk_evaluation_v2-c_s1000-200.csv
    week3_hitk_evaluation_v2-c_s300-50.csv
    week3_hitk_evaluation_v2-c_s400.csv
    week3_hitk_evaluation_v2-c_s700-100.csv
week 4/
  Week_4.ipynb
  result/
    week4_final_baseline_evaluation.csv
```

### Dataset

The `dataset/Initial stage/` directory contains the cleaned source document, the RAG knowledge base, and the phase 1 evaluation questions.

### Week 1: Retrieval

`week 1/Week_1.ipynb` evaluates MiniLM and MPNet retrieval and produces the retrieval result and summary CSV files.

### Week 2: LLM Comparison

`week 2/Week_2.ipynb` compares Gemma, Phi, and Qwen. The `result/` directory contains model-specific outputs and the comparison summary.

### Week 3: Hit@K Evaluation

`week 3/Week_3.ipynb` evaluates Hit@K retrieval performance across multiple chunking configurations. The corresponding CSV files in `week 3/result/` contain the evaluation outputs for each configuration.

### Week 4: Baseline Evaluation

`week 4/Week_4.ipynb` runs the final baseline evaluation. Its output is stored in `week 4/result/week4_final_baseline_evaluation.csv`.

## Workflow

1. Prepare and clean the RAG dataset.
2. Build the knowledge base and retrieval pipeline.
3. Evaluate retrieval quality with different embedding models.
4. Compare LLM answer quality and performance.
5. Evaluate Hit@K across chunking configurations.
6. Run the final baseline evaluation.

## Getting Started

### Requirements

- Python 3.8 or later
- Jupyter Notebook or JupyterLab
- The Python packages required by the notebooks

### Run a notebook

```bash
jupyter notebook "week 1/Week_1.ipynb"
jupyter notebook "week 2/Week_2.ipynb"
jupyter notebook "week 3/Week_3.ipynb"
jupyter notebook "week 4/Week_4.ipynb"
```

The local `venv/` directory is ignored by Git and should be used only for local dependencies.

## Repository

[FInal-Year-Project-Documentation](https://github.com/sahilc497/FInal-Year-Project-Documentation)

Last updated: 2026-08-19
