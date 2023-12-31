## Overview
This repository contains two Jupyter notebooks: `Content_Based_Filtering.ipynb` and `Collabrotive_Filtering.ipynb`, which focus on building a recommendation system for movies.

### `Content_Based_Filtering.ipynb`
- **Code Cells:** 11
- **Markdown Cells:** 3
- **Headings:**
  - TF-IDF with 2000 features
  - TF-IDF with 5000 features
  - TF-IDF with 10000 features
- **Key Libraries Used:**
  - `pandas`
  - `matplotlib.pyplot`
  - `sklearn.feature_extraction.text`
  - `sklearn.metrics.pairwise`
  - `ast`

### `Collabrotive_Filtering.ipynb`
- **Code Cells:** 15
- **Markdown Cells:** 6
- **Headings:**
  - User-Based
  - Item-Based
- **Key Libraries Used:**
  - `numpy`
  - `pandas`
  - `surprise`
  - `surprise.prediction_algorithms.knns`
  - `surprise.prediction_algorithms.matrix_factorization`

## Prerequisites
To run these notebooks, you need Python installed on your machine along with the following libraries:
- pandas
- matplotlib.pyplot
- sklearn
- numpy
- surprise

You can install these libraries using pip:

```bash
pip install pandas matplotlib sklearn numpy surprise
```

## Running the Notebooks
1. Clone this repository to your local machine.
2. Open the Jupyter Notebook (`.ipynb`) files in Jupyter Lab or Jupyter Notebook.
3. Run the cells in sequence to execute the code.

## Special Technical Requirements
Ensure that you have a Python environment capable of running Jupyter notebooks. Additionally, due to the computational nature of these notebooks, a machine with adequate memory and processing power is recommended.
