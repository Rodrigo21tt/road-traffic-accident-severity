# road-traffic-accident-severity
# Instructions to Reproduce the Results

This repository contains the code used to analyze road traffic accident severity using imbalanced and explainable machine learning techniques. All experiments were conducted in Python using a Jupyter Notebook environment.

## 1. Requirements

The experiments were executed using Python 3.9 or later.

The following libraries are required:
- numpy
- pandas
- scikit-learn
- imbalanced-learn
- matplotlib
- seaborn
- shap
- lime
- ipython
- jupyter

You can install all dependencies using:
pip install numpy pandas scikit-learn imbalanced-learn matplotlib seaborn shap lime ipython jupyter

## 2. Dataset

This project uses the US Accidents (2016–2023) dataset.
Due to size constraints, the dataset is not included in this repository.
The dataset can be downloaded from Kaggle:
https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents
The notebook assumes that the dataset file is located in the same directory as the notebook.
The dataset file may be named US_Accidents_March23.csv or an equivalent CSV file from the dataset.

## 3. Project Structure

The project directory should contain the following files:

- `individual.ipynb` : Main notebook containing all experiments  
- `US_Accidents_March23.csv` (or an equivalent dataset file)

## 4. How to Run the Experiments

1. Open a terminal in the project directory.
2. Launch Jupyter Notebook by running:
   jupyter notebook
3. Open the file `individual.ipynb`.
4. Run all cells sequentially from top to bottom.

The notebook includes:
- Data loading and preprocessing
- Feature engineering
- Handling of class imbalance
- Model training and evaluation
- Explainability analysis using SHAP and LIME
- Generation of figures and tables used in the report

## 5. Notes

- Due to the large size of the dataset, execution time may be significant.
- Some visualizations (e.g., SHAP plots) may take several minutes to compute.
- All results reported in the accompanying document were obtained directly from this notebook.
