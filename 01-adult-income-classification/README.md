# Adult Census Income Classification

## Objective

This project builds a machine-learning model to predict whether an individual's annual income is **more than $50K** or **$50K or less**, using census and employment-related information.

## Dataset

The project uses the UCI Adult Census Income dataset. It includes features such as age, education, work class, occupation, capital gain/loss, and weekly working hours.

## Libraries Used

- pandas
- NumPy
- scikit-learn

## Methodology

1. Loaded the Adult Census Income dataset.
2. Cleaned the dataset and prepared the target variable.
3. Split the data into training and testing sets.
4. Scaled numerical features and one-hot encoded categorical features.
5. Trained a Logistic Regression classification model.
6. Evaluated the model using accuracy, classification report, and confusion matrix.

## Results

- **Model:** Logistic Regression
- **Accuracy:** **85.60%**

The model predicts the income category with good baseline performance. Further improvements can be made using feature engineering and advanced models.

## Files

- `Adult-Income-Classification(1).ipynb` — Google Colab notebook containing the complete project code.

## How to Run

1. Open the notebook in Google Colab.
2. Run all cells from top to bottom.
3. The dataset will load automatically from the UCI repository.
