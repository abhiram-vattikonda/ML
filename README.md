# Machine Learning Lab Notebooks

This repository contains a set of Python/Jupyter notebooks for hands-on machine learning and data analysis labs. The notebooks cover core scientific Python tools, feature engineering, regression, classification, visualization, and applied exploratory analysis.

## Repository Contents

| File | Topic | Main Tools |
| --- | --- | --- |
| `lab1_AP23110010258.ipynb` | NumPy fundamentals, arrays, indexing, broadcasting, statistics, random numbers, linear algebra, file I/O, and a mini fitness-data project | NumPy |
| `lab2_AP23110010258.ipynb` | Pandas hands-on practice with exercises, reflection prompts, and a capstone workflow | Pandas, NumPy, Matplotlib, SQLite |
| `lab3_AP23110010258.ipynb` | Feature engineering concepts including missing-value handling, scaling, encoding, transformations, polynomial features, and PCA | Pandas, NumPy, scikit-learn, Matplotlib |
| `lab4_AP23110010258.ipynb` | Logistic regression workflow | Pandas, NumPy, Matplotlib, Seaborn |
| `Lab5_AP23110010258.ipynb` | Linear, polynomial, ridge, lasso, and elastic-net regression on wine-quality data | scikit-learn, Pandas, NumPy, Matplotlib, Seaborn |
| `Lab6_AP23110010258.ipynb` | K-nearest neighbors classification with preprocessing and class-balancing workflow | scikit-learn, imbalanced-learn, Pandas, NumPy, gdown |
| `Lab7_AP23110010258.ipynb` | Classification workflow using under-sampling and KNN | scikit-learn, imbalanced-learn, Pandas, NumPy, gdown |
| `Lab8_AP23110010258.ipynb` | Exploratory data analysis and visualization on tips data | Pandas, NumPy, Matplotlib, Seaborn |
| `Lab9_AP23110010258.ipynb` | Exploratory analysis of BMW worldwide sales records | KaggleHub, Pandas, NumPy, Matplotlib, Seaborn |
| `certs/` | Coursera certificate PDFs | PDF documents |

## Tech Stack

- Python 3
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
- imbalanced-learn
- gdown
- kagglehub

## Getting Started

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd ML
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   .venv\Scripts\activate
   ```

   On macOS/Linux:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. Install the recommended dependencies:

   ```bash
   pip install jupyter numpy pandas matplotlib seaborn scikit-learn imbalanced-learn gdown kagglehub
   ```

4. Start Jupyter:

   ```bash
   jupyter notebook
   ```

5. Open any notebook and run the cells from top to bottom.

## Notes

- Some notebooks download datasets from external sources such as Google Drive, UCI Machine Learning Repository, or Kaggle.
- `Lab9_AP23110010258.ipynb` uses KaggleHub. You may need Kaggle access configured on your machine before running the dataset-download cell.
- `Lab8_AP23110010258.ipynb` expects a `tips.csv` file to be available in the working directory.
- Notebook outputs are included in the files, so they can be reviewed directly on GitHub without rerunning every cell.

## Suggested Learning Path

1. Start with `lab1_AP23110010258.ipynb` for NumPy basics.
2. Continue with `lab2_AP23110010258.ipynb` for Pandas data manipulation.
3. Use `lab3_AP23110010258.ipynb` to understand feature engineering.
4. Move to `lab4_AP23110010258.ipynb` through `Lab7_AP23110010258.ipynb` for supervised learning workflows.
5. Finish with `Lab8_AP23110010258.ipynb` and `Lab9_AP23110010258.ipynb` for applied exploratory data analysis.

## License

No license has been specified yet. Add a license file if this repository will be shared or reused publicly.
