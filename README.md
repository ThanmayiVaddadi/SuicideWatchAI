# SuicideWatchAI

## Social Media-Based Ideation Detection using Genetic Algorithm Optimization

### About the Project

**SuicideWatchAI** is an AI-based project that analyzes social media text and identifies possible signs of suicidal ideation. The system uses Natural Language Processing (NLP), TF-IDF feature extraction, Genetic Algorithm-based feature selection, and Machine Learning for text classification.

### Objective

The main objective of this project is to develop an automated system that can analyze social media text and classify it based on the patterns learned from the dataset.

### Technologies Used

* **Python** – Main programming language
* **Flask** – Backend and web application
* **HTML** – Web page structure
* **CSS** – Web page design
* **JavaScript** – Used if required for frontend interaction
* **Pandas** – Dataset handling
* **NumPy** – Numerical operations
* **NLTK** – Natural Language Processing
* **Scikit-learn** – Machine Learning and evaluation
* **TF-IDF** – Text feature extraction
* **Genetic Algorithm** – Feature selection and optimization
* **Joblib/Pickle** – Saving and loading the trained model

### System Flow

Dataset
↓
Data Cleaning
↓
Text Preprocessing
↓
TF-IDF Feature Extraction
↓
Genetic Algorithm Feature Selection
↓
Machine Learning Classification
↓
Model Evaluation
↓
Prediction

### Main Modules

1. **Dataset Module** – Loads and checks the dataset.
2. **Preprocessing Module** – Cleans and prepares the text.
3. **Feature Extraction Module** – Converts text into numerical features using TF-IDF.
4. **Genetic Algorithm Module** – Selects important features.
5. **Machine Learning Module** – Trains the classification model.
6. **Evaluation Module** – Measures model performance.
7. **Prediction Module** – Predicts the class of new text.
8. **Web Application** – Provides a simple interface for entering text and viewing the prediction.

### Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

The baseline model and GA-optimized model can be compared to understand the effect of feature optimization.

### Running the Project

Install the required Python libraries:

```bash
pip install -r requirements.txt
```

Run the Flask application:

```bash
python app.py
```

Then open the application in a web browser:

```text
http://127.0.0.1:5000/
```

### Disclaimer

This project is developed for **academic and research purposes**. The predictions should not be considered a medical diagnosis or a replacement for professional mental-health assessment.

### Project

**Project Name:** SuicideWatchAI
**Topic:** Social Media-Based Ideation Detection using Genetic Algorithm Optimization
