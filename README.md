# Climate-ML-Toolkit
🌍 A comprehensive machine learning toolkit for climate data analysis, integrating Regression, Classification, and Clustering methods to analyze and predict temperature trends using NOAA data and written in Google Colab.

## 📊 Features
- **Regression (Forecasting)** → Predicts future temperatures using Decision Tree & Random Forest.
- **Classification (Weather Categories)** → Classifies days as Cold, Mild, or Hot using Naive Bayes.
- **Clustering (Seasonal Pattern Detection)** → Identifies weather patterns using Hierarchical Clustering.
- **Data Source** → NOAA historical climate data for NYC (2018-2023).

## 🚀 How to Use
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
2. Run temperature prediction:
   ```bash
   python models/regression.py
3. Run weather classification
   ```bash
   python models/classification.py
4. Run clustering analysis:
   ```bash
   python models/clustering.py

## 📂 Project Structure
   ``` css
📂 climate-ml-toolkit
├── 📄 README.md
├── 📂 data ← Climate datasets
| ├── nyc_climate.csv ← NOAA weather data
├── 📂 models ← Machine learning models
│ ├── regression.py ← Temperature prediction
│ ├── classification.py ← Weather classification
│ ├── clustering.py ← Hierarchical clustering
├── 📂 notebooks ← Jupyter Notebooks version
│ ├── regression.ipynb ← Regression analysis
│ ├── classification.ipynb ← Classification notebook
│ ├── clustering.ipynb ← Clustering notebook
