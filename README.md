# EEG Driver Drowsiness Detection

Classifying drowsy vs non-drowsy drivers using EEG brainwave data.

## Dataset
Sleepy Driver EEG Brainwave Dataset (Kaggle) — 3735 samples, 8 frequency band features

## Models Tried
| Model | Accuracy |
|-------|----------|
| SVM | 69.0% |
| XGBoost | 76.0% |
| MLP | 75.7% |
| CNN | 73.9% |
| Random Forest | 77.2% |

## Key Finding
Random Forest outperformed deep learning models because the dataset contains 
pre extracted frequency bands, not raw EEG signals. RF handles structured 
tabular data better in this case.

## Tech Stack
Python, Scikit-learn, TensorFlow, Keras, Pandas, NumPy
