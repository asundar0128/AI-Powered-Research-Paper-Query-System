## Biopharma Intelligence: Agentic Research Query Systemr  

## Overview
This project is a high-precision intelligence tool designed to bridge the gap between academic research and industrial application. By leveraging the **PubMed/MEDLINE API**, it identifies and extracts research papers that feature **non-academic corporate affiliations** (Biotech, Pharma, and Life Sciences). 

In the era of Agentic AI, this tool serves as a foundational data-gathering layer for competitive intelligence and identifying industry-academia collaborations.

## Key Features
- **Semantic Filtering:** Advanced heuristic engine to distinguish between academic institutions (universities/hospitals) and corporate entities.
- **MEDLINE Deep Parsing:** Extracts granular metadata including PubMed IDs, Title, Publication Year, and Company Affiliations.
- **Ground Truth Reliability:** Directly interfaces with the National Center for Biotechnology Information (NCBI) to ensure 0% hallucination in source data.
- **Production-Ready Architecture:** - Fully typed Python code for enterprise maintainability.
  - Modular CLI interface for easy integration into larger CI/CD pipelines.
  - Efficient dependency management via **Poetry**.

## Tech Stack
- **Language:** Python 3.9+
- **APIs:** [Biopython (Entrez)](https://biopython.org/)
- **Data Engineering:** [Pandas](https://pandas.pydata.org/)
- **UX:** [TQDM](https://tqdm.github.io/) for real-time progress tracking
- **Environment:** Poetry

## Installation

```bash
# Install Poetry (if not already installed)
curl -sSL [https://install.python-poetry.org](https://install.python-poetry.org) | python3 -

# Clone and enter the repository
git clone [https://github.com/asundar0128/ResearchPapersQuery.git](https://github.com/asundar0128/ResearchPapersQuery.git)
cd ResearchPapersQuery/pubmed_fetcher_project

# Install dependencies
poetry install
```

## Usage

