# Sonar-Rock-VS-Mine-Predictor

Sonar Rock vs Mine Prediction using Machine Learning

A machine learning project that predicts whether an underwater object detected by sonar is a Rock (R) or a Mine (M) using Logistic Regression and the Sonar Dataset.

Project Overview

Sonar systems send sound waves underwater and analyze the reflected signals. Different objects reflect sound differently. This project uses those sonar signal values to classify objects into:

* R → Rock
* M → Mine

The model is trained using Logistic Regression from Scikit-learn.

⸻

Features

* Data preprocessing using Pandas
* Data analysis and exploration
* Splitting data into training and testing datasets
* Logistic Regression model training
* Model evaluation using accuracy score
* Prediction system for new sonar inputs
* Built without Jupyter Notebook using a clean Python project structure

⸻

Project Structure

Sonar-Rock-VS-Mine-Predictor/
│
├── src/
│   ├── train.py
│   └── Copy of sonar data.csv
│
├── .venv/
├── README.md
├── requirements.txt
└── .gitignore

⸻

Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn

⸻

Installation

Clone the repository:

git clone https://github.com/Hellboy28D/Sonar-Rock-VS-Mine-Predictor.git

Move into the project directory:

cd Sonar-Rock-VS-Mine-Predictor

Create virtual environment:

python -m venv .venv

Activate environment:

Mac/Linux:

source .venv/bin/activate

Windows:

.venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

⸻

Running the Project

Run:

python src/train.py

⸻

Model Workflow

1. Load sonar dataset
2. Explore and analyze data
3. Separate features and labels
4. Split data into training and testing data
5. Train Logistic Regression model
6. Evaluate model performance
7. Predict Rock or Mine

⸻

Example Output

Accuracy on training data: 0.83
Accuracy on test data: 0.76
['R']
The object is a Rock

⸻

Dataset Information

* Total samples: 208
* Features: 60
* Output classes:
    * R = Rock
    * M = Mine

⸻

Future Improvements

* Build a Streamlit web app interface
* Save trained model using Pickle
* Deploy using Render or Hugging Face Spaces
* Try different algorithms:
    * Random Forest
    * SVM
    * XGBoost
    * Neural Networks

⸻

Author

Divakr (Hellboy28D)

GitHub: https://github.com/Hellboy28D

⸻

License

This project is open-source and available under the MIT License.
