# Heart Disease Analysis and Prediction

## Project Overview
This project uses exploratory data analysis (EDA) and a
Multilayer Perceptron (MLP) neural network to analyze the
TenYearCHD outcome in the Framingham Heart Study dataset.
Logistic regression is used as a baseline model.

## Dataset
Source:
https://www.kaggle.com/datasets/aasheesh200/framingham-heart-study-dataset

The analyzed CSV contains 4,240 rows and 16 columns.
Target variable: `TenYearCHD`.

Please review the dataset's license and terms before
redistributing the raw data.

## Technologies
- Python
- pandas and NumPy
- Matplotlib and Seaborn
- scikit-learn
- TensorFlow/Keras
- Google Colab

## Repository Structure
- `Heart_Disease_Analysis_and_Prediction.ipynb`:
  notebook containing the analysis and model
- `Heart_Disease_Project_Report.docx`: project report
- `evaluation_results/`: exported evaluation metrics and CSVs
- `visualizations/`: exported EDA and model figures
- `README.md`: project documentation

## How to Run
1. Open the notebook in Google Colab.
2. Download the dataset from the source link above.
3. Upload the CSV when prompted by the notebook.
4. Run the cells in order.
5. Review the generated figures and evaluation results.

## Results
The provided comparison showed:
- Logistic Regression ROC-AUC: 0.697
- MLP Neural Network ROC-AUC: 0.688

Logistic regression performed better on the reported comparison
metrics. See `evaluation_results/` for exported results.

## Limitations
This is an educational project, not a clinically validated
diagnostic tool. Results depend on the dataset and evaluation split.

## Author
Ashwiniya P V
