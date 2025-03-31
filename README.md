# Credit-Card-Fraud-Detection
Fraud Detection using Machine Learning

Machine learning-based fraud detection system to detect fraudulent transactions as opposed to legitimate transactions. The system uses transactional data, location data, and machine learning models to detect fraudulent transactions more accurately with fewer false positives.

Features:

User Authentication: Not done here, but can be included for secure login.

Data Preprocessing:

Handling missing values and one-hot encoding.

Date-time feature creation.

Computing transaction distances based on the Haversine formula.

Model Training & Evaluation

Uses Random Forest Classifier for detection of fraud.

Performs evaluation on model performance regarding accuracy, precision, recall, and confusion matrix.

Visualization:
Heatmaps, confusion matrices with Matplotlib & Seaborn.

Data Storage: The data are processed and read from CSV files.

Project Structure

fraud-detection/
├── README.md
├── fraud_detection.py  # Training and eval script
├── data/
│   └── fraud_data.csv  # Data file
├── models/
│   └── fraud_model.pkl  # Saved model (if any)
├── preprocessing/
│   └── feature_engineering.py  # Feature extraction & preprocessing functions
├── utils/
│   └── haversine.py  # Transaction distance computation function
│   └── data_loader.py  # Data loading & preprocessing function
└── visualization/
└── plot_results.py  # Confusion matrix & evaluation plotter

Installation Steps

1. Clone the repo:
git clone https://github.com/yourusername/fraud-detection.git

2. Move into project directory:
cd fraud-detection

3. Install dependencies:

pip install -r requirements.txt

4. Run the fraud detection script:

python fraud_detection.py

Dependencies (requirements.txt)

pandas
numpy
matplotlib
seaborn
scikit-learn

Additional Resources

Scikit-Learn Documentation

Pandas Documentation

Matplotlib Documentation
