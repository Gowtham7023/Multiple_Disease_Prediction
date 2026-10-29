# Multiple Disease Prediction System

A Streamlit web application that predicts multiple diseases using Machine Learning models. Currently supports:
- 🩸 **Diabetes Prediction**
- ❤️ **Heart Disease Prediction**
- 🧠 **Parkinson's Disease Prediction**

## Author
**Gowtham**

## Project Structure
```
├── app.py                          # Main Streamlit application
├── requirements.txt                # Python dependencies
├── dataset/                        # Training datasets (CSV)
│   ├── diabetes.csv
│   ├── heart.csv
│   └── parkinsons.csv
├── saved_models/                   # Pre-trained ML models
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   └── parkinsons_model.sav
└── colab_files_to_train_models/    # Jupyter notebooks used for training
    ├── Multiple disease prediction system - diabetes.ipynb
    ├── Multiple disease prediction system - heart.ipynb
    └── Multiple disease prediction system - Parkinsons.ipynb
```

## Setup & Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/Multiple-Disease-Prediction.git
   cd Multiple-Disease-Prediction
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app**
   ```bash
   streamlit run app.py
   ```

## Technologies Used
- Python
- Streamlit
- Scikit-learn
- NumPy / Pandas

## License
This project is open source and available for personal and educational use.
