# SingleCellRNASeq-DataAnalysis

This repository contains Python code for implementing data analysis on single-cell RNA sequencing. The project is divided into two tasks:

## Task A: Choice of Features

In this task, we implement and compare four feature selection methods and evaluate their efficiency when used with the k-nearest neighbors (kNN) algorithm. The implemented feature selection methods are applied to select the best features within a threshold. We demonstrate the performance of the kNN classifier for each combination of the top features, ranging from 1 to 300.

## Task B: Classification with Ensemble Classifiers

In this task, we perform and compare four ensemble techniques for classification. The implemented ensemble techniques include Random Forest, XGBoost, CatBoost, and Bootstrap Aggregation (Bagging). We evaluate and compare the performance of these ensemble classifiers on the chosen dataset.

## Dataset

The dataset used for this project can be downloaded from the following link:

[Dataset Link](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE75688)

Please download the dataset and place it in the `data` directory before running the code.

## Getting Started with Task A

To run the code for Task A, follow the steps below:

1. Download the code file (`taskA.ipynb`) from the `src/taskA` directory in this repository.

2. Set up Anaconda environment:
   - Ensure that you have Anaconda installed on your system.
   - Create a new Anaconda environment or use an existing one for this project.

3. Open the Anaconda Navigator:
   - Activate the desired Anaconda environment.
   - Launch Jupyter Notebook or JupyterLab.

4. In the Jupyter interface, navigate to the location where you downloaded the `taskA.ipynb` file.

5. Open `taskA.ipynb` by clicking on it.

6. Execute the notebook:
   - Go through the code cells and ensure that you have all the required dependencies installed (e.g., `numpy`, `scikit-learn`).
   - Run each code cell sequentially by clicking on it and pressing Shift+Enter or by using the Run button in the Jupyter interface.

7. The code will be executed, and you will see the output and results in the notebook.

> **Note**: Before running the code, make sure that you have also downloaded the dataset and placed it in the `data` folder along with the `Series_Matrix.xlsx` file.

## Getting Started with Task B

To run the code for Task B, follow the steps below:

1. Download the code file (`taskB.ipynb`) from the `src/taskB` directory in this repository.

2. Set up Anaconda environment:
   - Ensure that you have Anaconda installed on your system.
   - Create a new Anaconda environment or use an existing one for this project.

3. Open the Anaconda Navigator:
   - Activate the desired Anaconda environment.
   - Launch Jupyter Notebook or JupyterLab.

4. In the Jupyter interface, navigate to the location where you downloaded the `taskB.ipynb` file.

5. Open `taskB.ipynb` by clicking on it.

6. Execute the notebook:
   - Go through the code cells and ensure that you have all the required dependencies installed (e.g., `numpy`, `scikit-learn`).
   - Run each code cell sequentially by clicking on it and pressing Shift+Enter or by using the Run button in the Jupyter interface.

7. The code will be executed, and you will see the output and results in the notebook.

> **Note**: Before running the code, make sure that you have also downloaded the dataset and placed it in the `data` folder.

If you have any issues or questions, feel free to reach out. Happy analyzing!
