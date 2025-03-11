

## Instructions for Running the Code

1. **Environment Setup**:
   - Ensure Python 3.8 or later is installed.
   - Install the required libraries by running:
     ```bash
     pip install pandas numpy scikit-learn matplotlib seaborn
     ```

2. **Dataset Preparation**:
   - Download the datasets from the following URLs:
     - Industrial Equipment Monitoring Dataset: [Kaggle Link]
     - Machine Failure Prediction Dataset: [Kaggle Link]
   - Place the datasets in the `data` folder.

3. **Running the Code**:
   - Open the Jupyter Notebook for the desired dataset:
     - `Industrial_Equipment_Monitoring.ipynb`
     - `Machine_Failure_Prediction.ipynb`
   - Execute the cells in the notebook to preprocess the data, train the models, and generate visualizations.

4. **Reproducing Results**:
   - Ensure the random seed is set to `42` for reproducibility.
   - Follow the preprocessing steps outlined in the notebooks.

## Supporting Information

- **Dataset URLs**:
  - Industrial Equipment Monitoring Dataset: [Kaggle Link]
  - Machine Failure Prediction Dataset: [Kaggle Link]

- **Preprocessing Steps**:
  - Missing values are handled using mean imputation.
  - Categorical attributes are one-hot encoded.
  - Numerical features are standardized using `StandardScaler`.

- **Hyperparameter Tuning**:
  - All models use `GridSearchCV` for hyperparameter tuning.

- **Visualizations**:
  - Learning curves, confusion matrices, and feature importance plots are generated for each model.

## Contact Information

For any questions or issues, please contact:
- Name: Francis Chapoterera
- Email: chapoterera.f@northeastern.edu
