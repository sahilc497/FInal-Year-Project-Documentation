# Final Year Project Documentation

Welcome to the Final Year Project Documentation repository. This project contains resources and documentation for RAG (Retrieval-Augmented Generation) retrieval experiments and analysis.

## Project Overview

This project includes:
- RAG knowledge base and cleaned documents
- Jupyter notebook for Week 1 analysis
- Retrieval results from different models (MiniLM and MPNet)
- Retrieval summary and evaluation metrics

## Folder Structure

```
Mega Project/
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
└── venv/
    └── [Python virtual environment]
```

## Contents

### Dataset
- **Initial stage/**: Contains the initial stage documents and knowledge base
  - `cleaned_rag_document.txt`: Cleaned RAG document for retrieval
  - `rag_knowledge_base.txt.txt`: RAG knowledge base
  - `phase 1 questions.docx`: Phase 1 questions document

### Week 1 Analysis
- **Week_1.ipynb**: Jupyter notebook containing analysis for week 1
- **results/**: Directory containing retrieval results from different models
  - `minilm_retrieval_results.csv`: Retrieval results using MiniLM model
  - `mpnet_retrieval_results.csv`: Retrieval results using MPNet model
  - `retrieval_summary.csv`: Summary of retrieval results across models

## Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- Required packages (listed in requirements.txt if available)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/sahilc497/FInal-Year-Project-Documentation.git
cd "Mega Project"
```

2. Create and activate virtual environment:
```bash
python -m venv venv
venv\Scripts\activate  # On Windows
source venv/bin/activate  # On macOS/Linux
```

3. Install dependencies (if requirements.txt exists):
```bash
pip install -r requirements.txt
```

### Running the Notebook

To view and run the analysis notebook:
```bash
jupyter notebook "week 1/Week_1.ipynb"
```

## Models Used

- **MiniLM**: Lightweight retrieval model with good performance
- **MPNet**: Multi-perspective encoder-decoder model for retrieval tasks

## Results

The retrieval results from both models are stored in CSV format in the `week 1/results/` directory. The summary includes:
- Retrieval accuracy metrics
- Query-document relevance scores
- Model performance comparison

## Contributing

For questions or contributions, please contact the project owner.

## License

This project is part of a Final Year academic project.

---

**Repository**: [FInal-Year-Project-Documentation](https://github.com/sahilc497/FInal-Year-Project-Documentation)

**Last Updated**: 2026-08-15
