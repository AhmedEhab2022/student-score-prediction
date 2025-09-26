# Student Score Prediction

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AhmedEhab2022/student-score-prediction/blob/main/Student_Score_Prediction.ipynb)

Predict student exam scores using real-world factors with machine learning. This Colab-ready notebook covers data cleaning, analysis, feature engineering, and regression modeling, with visualizations and performance evaluation.

## Dataset

The dataset `StudentPerformanceFactors.csv` is sourced from [Kaggle](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors) and contains various factors that influence student academic performance, including:

- Hours studied
- Sleep hours
- Attendance
- Teacher quality
- School type
- Family income
- Parental involvement
- Previous scores
- And more...

## Project Structure

```
├── StudentPerformanceFactors.csv    # Dataset from Kaggle
├── Student_Score_Prediction.ipynb   # Main analysis notebook
├── requirements.txt                 # Python dependencies
├── README.md                        # Project documentation
└── LICENSE                          # MIT License
```

## Features

- **Data Cleaning**: Handle missing values and duplicate entries
- **Exploratory Data Analysis**: Visualizations using matplotlib, seaborn, and plotly
- **Feature Engineering**: Encode categorical variables and select relevant features
- **Machine Learning Models**:
  - Linear Regression
  - Polynomial Regression
- **Model Evaluation**: MSE, RMSE, R² scores with comparison visualizations
- **Google Colab Ready**: Includes drive mounting and package installation

## How to Run

### Option 1: Google Colab (Recommended)

1. Click the "Open in Colab" badge above
2. Upload the dataset to your Google Drive in the appropriate folder
3. Run all cells in sequence

### Option 2: Local Setup

1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open `Student_Score_Prediction.ipynb` in Jupyter
4. Update the data path to point to your local dataset
5. Run all cells

## Results

The notebook demonstrates that:

- Linear regression performs well for this approximately linear dataset
- Additional relevant features improve model performance
- Polynomial regression doesn't provide a significant improvement for this dataset
- Feature selection impacts model accuracy

## Requirements

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- plotly
- jupyter

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Data Source

Dataset: [Student Performance Factors](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors) from Kaggle
