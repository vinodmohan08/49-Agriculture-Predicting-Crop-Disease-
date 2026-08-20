# Agriculture: Predicting Crop Disease (Early-Warning ML System)

## Problem Overview
An end-to-end Machine Learning pipeline to predict crop disease outbreaks from environmental microclimates, soil conditions, and agricultural inputs.

## Dataset
- **Source**: Kaggle (Agricultural Crop & Disease Synthetic Dataset)
- **Features**: Temperature, Humidity, Rainfall, Soil pH, Soil Moisture, Fertilizer Usage, Yield, Season, Crop History.

##  Tech Stack & Dependencies
- Python 3.10+
- NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, Joblib

## Key Results
| Model | Accuracy | Precision (Weighted) | Recall (Weighted) | F1-Score (Weighted) |
|---|---|---|---|---|
| **Decision Tree** | 88.45% | 88.60% | 88.45% | 88.52% |
| **SVM (RBF Kernel)** | 91.30% | 91.45% | 91.30% | 91.37% |

## Top Driving Factors
1. Yield / Output Stress (47.77%)
2. Seasonal Dynamics (21.25%)
3. Nitrogen Application (13.01%)
4. Precipitation & Ambient Humidity (11.20% combined)

## How to Run
1. Clone the repository: `git clone https://github.com/<your-username>/crop-disease-prediction.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Launch Jupyter Notebook: `jupyter notebook notebooks/agriculture_disease_prediction.ipynb`