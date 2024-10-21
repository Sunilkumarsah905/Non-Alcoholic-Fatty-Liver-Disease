# Non-Alcoholic-Fatty-Liver-Disease
AUTOMATED PREDICTION OF NON-ALCOHOLIC FATTY LIVER DISEASE USING MACHINE LEARNING ALGORITHMS---

## Abstract
The prevalence of obesity has lead the metabolic syndrome Non- Alcoholic Fatty Liver Disease (NAFLD) to be a serious health concern over the years. Early prediction on liver disease using classification algorithm is an efficacious task that can help the doctors to diagnose the disease within a short period of time. The main objective of this project is to identify the potential factors causing NAFLD by using Machine Learning algorithms like Random Forest classifier algorithm.

Keywords: Automatic Prediction, Fatty liver detection, Random forest classification algorithm, Machine Learning, Standard Scalar Normalization, Data Preparation.

(Non-Alcoholic Fatty Liver Disease (NAFLD) is a common liver condition characterized by excessive fat accumulation in the liver in individuals who consume little or no alcohol. Early diagnosis and effective prediction are critical for preventing progression to more severe liver diseases. This project implements automated prediction models using various machine learning algorithms, leveraging patient data to identify individuals at risk for NAFLD. By analyzing factors such as age, gender, body mass index (BMI), and laboratory results, this project aims to enhance predictive accuracy and facilitate timely medical intervention.)

## Table of Contents
- [Abstract](#abstract)
- [Project Description](#project-description)
- [Introduction](#introduction)
- [Purpose of the System](#purpose-of-the-system)
- [Scope of the System](#scope-of-the-system)
- [Current System](#current-system)
- [Proposed System](#proposed-system)
- [Technologies Used](#technologies-used)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Machine Learning Models](#machine-learning-models)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Description
This project focuses on developing machine learning models to predict the likelihood of NAFLD in patients. Using a dataset that includes a variety of clinical and demographic features, the goal is to provide healthcare professionals with a tool to assess the risk of NAFLD effectively.

## INTRODUCTION
The prevalence of obesity has led the metabolic syndrome Non- Alcoholic Fatty Liver Disease (NAFLD) to be a serious health concern over the years. Early prediction on liver disease using classification algorithm is an efficacious task that can help the doctors to diagnose the disease within a short period of time. The main objective of this project is to identify the potential factors causing NAFLD by using Machine Learning algorithms like Random Forest classifier.

## Purpose of the System
Non-Alcoholic Fatty Liver Disease or NAFLD is a common and rising entity which leads to various liver disorders. Its prevalence is increasing at a rapid rate due to the increasing levels of obesity, diabetic patients and hypertension. These disorders are where the liver damage is unrelated to alcohol consumption. There are various methods to detect this early in order for quick treatment and recovery as in some cases this could be fatal.

## Scope of the System
- The patient gets to know if he or she has fatty liver disease or not.
- Separate analysis for men and women.
- Separate analysis based on age.

## Current System
- In existing system electronic health records from the Optum Analytics to (1)
identify patients diagnosed with benign steatosis and NASH, and (2) train machine learning classifiers for NASH and healthy (non-NASH) populations to (3) predict NASH disease status on patients diagnosed with NAFL. Summarized temporal lab data for alanine aminotransferase, aspartate aminotransferase, and platelet counts, with basic demographic information and type 2 diabetes status were included in the models.
- It was not until 2015 that M.Birjandi et al. [11] made use of classification tree, a non-parametric statistical learning approach, to diagnose NAFLD and identify its associated factors in the area.

## Proposed System
Proposed system study is to identify the potential factors of NAFLD first and then apply machine learning methods to the health examination data to construct the learning system. We observed that metabolic syndrome, body mass index, triglyceride, total cholesterol, age, waist to hip ratio, high density lipoprotein cholesterol, low-density lipoprotein cholesterol might be the risk factors of NAFLD.


## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib/Seaborn (for visualization)
- Jupyter Notebook

## Data
The dataset used for this project is sourced from [insert data source, e.g., UCI Machine Learning Repository, Kaggle]. It contains features including but not limited to:
- Age
- Gender
- Body Mass Index (BMI)
- Liver enzyme levels (ALT, AST)
- Blood glucose levels
- Cholesterol levels

Refer to the dataset documentation for detailed descriptions of each feature.

## Installation
To set up the project environment, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Non-Alcoholic-Fatty-Liver-Disease.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Non-Alcoholic-Fatty-Liver-Disease
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To run the model training and prediction, execute the Jupyter Notebook provided in the repository:
```bash
jupyter notebook NAFLD_Prediction.ipynb
```

## Machine Learning Models
This project implements the following algorithms:
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machine (SVM)
- Gradient Boosting

Each model is evaluated based on performance metrics such as accuracy, precision, recall, and F1 score.

## Results
The results section includes visualizations of model performance and key findings. A comparison of model accuracy and effectiveness is provided to highlight the best-performing algorithm for NAFLD prediction.

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to modify any section or add specific details relevant to your project!
