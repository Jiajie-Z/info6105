## How to Run the Project

This repository contains the full workflow for a tennis match outcome prediction project, including data preparation, EDA, modeling, prediction demo, and an optional Streamlit app.  
Follow the steps below to reproduce all results.

---

### 1. Clone the repository

```bash
git clone <your_repo_url>
cd <your_repo_name>


make sure you have Jupyter Notebook installed and then run the following command in Command:

jupyter notebook Notebooks/eda_tennis.ipynb

jupyter notebook Notebooks/modeling_tennis.ipynb

jupyter notebook Notebooks/demo_final.ipynb


Reproducibility Notes

The model depends only on pre-match features.

All notebooks can be re-run end-to-end to regenerate the same cleaned dataset and model.

Random seeds are set for reproducibility where applicable.