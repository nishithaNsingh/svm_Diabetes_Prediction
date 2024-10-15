# SVM Diabetes Prediction

This project uses a Support Vector Machine (SVM) algorithm to predict whether a person has diabetes based on medical input data. The dataset used for training the model contains various health metrics that are indicative of diabetes.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Technologies](#technologies)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview
The SVM Diabetes Prediction model is developed using Python. It leverages the SVM algorithm to classify whether an individual is diabetic based on a set of features such as glucose levels, blood pressure, skin thickness, insulin levels, BMI, and more.

## Features
- **Data Preprocessing:** Handles missing data and normalizes the dataset.
- **Model Training:** Uses Support Vector Machine (SVM) for classification.
- **Prediction:** Provides an easy-to-use interface for making predictions.
- **Evaluation:** Measures model performance using accuracy and other metrics.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/nishithaNsingh/svm_Diabetes_Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd svm_Diabetes_Prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the Jupyter notebook to see the data analysis, model training, and prediction process:
   ```bash
   jupyter notebook SVM_Diabetes_Prediction.ipynb
   ```
2. Follow the steps in the notebook to understand how the model is trained and evaluated.

## Dataset
The dataset used for this project is the PIMA Indians Diabetes Dataset, which contains several medical predictor variables and one target variable, Outcome. The predictor variables include:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

The dataset is available in the repository under the `data/` folder.

## Technologies
- **Programming Language:** Python
- **Libraries:** 
  - Pandas
  - NumPy
  - scikit-learn
  - matplotlib
  - seaborn

## Results
The SVM model has been evaluated for accuracy, precision, recall, and F1-score. The detailed results can be found in the notebook.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any questions or inquiries, feel free to reach out:
- **Author:** Nishitha Singh
- **GitHub:** [nishithaNsingh](https://github.com/nishithaNsingh)
