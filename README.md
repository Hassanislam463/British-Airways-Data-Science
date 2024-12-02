# British Airways Customer Insights and Booking Prediction

This repository contains two related projects that aim to analyze customer reviews and predict booking behavior for British Airways. By leveraging data science and machine learning, these projects provide actionable insights and predictive capabilities to improve customer experience and operational efficiency.

---

## Project 1: Customer Review Analysis

### Objective
To analyze customer reviews from Skytrax and derive insights regarding customer sentiment and common topics discussed.

### Highlights
- **Data Collection**: Web scraping customer reviews using Python.
- **Data Analysis**: 
  - Sentiment Analysis: Identified 64% positive reviews and 36% negative reviews.
  - Topic Modeling: Explored key themes such as service quality, flight delays, and crew performance.
  - Word Cloud Visualization: Highlighted frequently mentioned terms.
- **Presentation**: A concise PowerPoint slide summarizing insights with visualizations and metrics.

### Deliverables
- Data preparation and analysis scripts:
  - `notebooks/Task1.ipynb`
  - `notebooks/Task1_main.ipynb`
- Insights presentation:
  - `insights/Presentation.pptx`

---

## Project 2: Booking Prediction Model

### Objective
To predict whether a customer will complete a booking using a machine learning model.

### Highlights
- **Data Preparation**: 
  - Feature engineering to enhance dataset quality.
  - Handling class imbalance to improve model performance.
- **Model Training**: 
  - Trained a Random Forest model with 85.06% accuracy.
  - Identified variable importance for better interpretability.
- **Evaluation**:
  - Metrics such as precision, recall, and a confusion matrix highlight the model's performance.
  - Next steps include addressing class imbalance to improve predictions for "Booking Completed."
- **Presentation**: A single-slide summary with visualizations and insights.

### Deliverables
- Data preparation and modeling scripts:
  - `notebooks/Main.ipynb`
- Insights presentation:
  - `insights/Presentation_2.pptx`

---

## Getting Started

### Prerequisites
- Python 3.7 or higher.
- Required libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`
  - Any other dependencies listed in the notebooks.
- Jupyter Notebook to run the analysis.
