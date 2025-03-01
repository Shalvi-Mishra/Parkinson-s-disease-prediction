# Parkinson's Disease Prediction

## Overview
This project aims to predict Parkinson's disease using machine learning techniques. Parkinson's disease is a neurodegenerative disorder that affects movement. Early detection is crucial for better management and treatment.

The model is trained on biomedical voice measurements to classify whether a person has Parkinson's disease.

## Dataset
The dataset used for this project contains biomedical voice measurements from individuals, with features such as:
- **MDVP:** Several variations of fundamental frequency (Fo, Fhi, Flo)
- **Jitter and Shimmer:** Measures of frequency and amplitude variations
- **Harmonic-to-Noise Ratio (HNR)**
- **Spread, PPE, D2, DFA:** Nonlinear dynamical complexity measures

## Installation
To set up this project, follow these steps:

```bash
# Clone the repository
git clone https://github.com/yourusername/parkinsons-disease-prediction.git
cd parkinsons-disease-prediction

# Create a virtual environment (optional)
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Usage
To run the model and make predictions:

```python
# Run the Jupyter Notebook
jupyter notebook Parkinson's_disease_prediction.ipynb
```

Alternatively, if the script version is available:

```bash
python predict.py --input_file sample_data.csv
```

## Model
The machine learning model implemented includes:
- **Feature Selection:** Identifies important voice-related biomarkers.
- **Preprocessing:** Handles missing values, scaling, and normalization.
- **Algorithms Used:** Random Forest, Support Vector Machine (SVM), or Neural Networks.
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, ROC-AUC.

## Results
- Achieved **X% accuracy** on test data.
- Feature importance analysis showed that `Jitter(%)`, `HNR`, and `Fo` were among the most significant features.
- Confusion matrix and classification report show promising results for early detection.

## Future Improvements
- **Feature Engineering:** Extract additional voice characteristics to enhance predictions.
- **Hyperparameter Tuning:** Use GridSearchCV or Bayesian Optimization to improve model performance.
- **Deep Learning Integration:** Experiment with LSTMs or CNNs for better feature extraction.
- **Deployment:** Convert the model into a web application using Flask or FastAPI.

## Contributing
If you'd like to contribute, follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make changes and commit (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.



## Contact
For questions or collaborations, feel free to reach out:
- **Email:** shalvimishra26280@gmail.com
- **GitHub:** https://github.com/Shalvi-Mishra

