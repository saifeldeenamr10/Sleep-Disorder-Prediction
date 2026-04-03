# 🌙 Sleep Disorder Prediction

![Sleep Disorder](https://mpowerminds.com/assetOLD/images/sleep-disorder.jpg)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![Scikit-learn](https://img.shields.io/badge/scikit--learn-0.24%2B-orange.svg)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/pandas-1.3%2B-green.svg)](https://pandas.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A comprehensive data science project that analyzes lifestyle and medical factors to predict sleep disorders using machine learning techniques.

## 📋 Project Overview

This project aims to predict the occurrence and type of sleep disorders (Insomnia and Sleep Apnea) by analyzing various lifestyle and medical variables including age, BMI, physical activity, sleep duration, blood pressure, and more. Early identification of individuals at risk enables appropriate interventions and treatments to improve sleep quality and overall health.

## 🎯 Key Objectives

- **Analyze** comprehensive sleep metrics and lifestyle factors
- **Identify** key predictors of sleep disorders
- **Build** accurate machine learning models for prediction
- **Provide** actionable insights for sleep health improvement

## 📊 Dataset

The **Sleep Health and Lifestyle Dataset** contains 400 records with 13 features covering sleep patterns, daily habits, and health indicators.

### Data Dictionary

| Column Name         | Description                                          | Type        |
| ------------------- | ---------------------------------------------------- | ----------- |
| `Person_ID`         | Unique identifier for each individual                | Integer     |
| `Gender`            | Gender of the person (Male/Female)                   | Categorical |
| `Age`               | Age in years                                         | Integer     |
| `Occupation`        | Professional occupation                              | Categorical |
| `Sleep_duration`    | Daily sleep duration in hours                        | Float       |
| `Quality_of_sleep`  | Subjective sleep quality rating (1-10)               | Integer     |
| `Physical_activity` | Activity level (Low/Medium/High)                     | Categorical |
| `Stress_Level`      | Subjective stress rating (1-10)                      | Integer     |
| `BMI_category`      | BMI category (Underweight/Normal/Overweight/Obesity) | Categorical |
| `Blood_pressure`    | Blood pressure in mmHg                               | String      |
| `Heart_rate`        | Heart rate in beats per minute                       | Integer     |
| `Daily_Steps`       | Daily step count                                     | Integer     |
| `Sleep_disorder`    | Sleep disorder type (None/Insomnia/Sleep Apnea)      | Categorical |

### Sleep Disorder Categories

- **None**: No specific sleep disorder detected
- **Insomnia**: Difficulty falling or staying asleep
- **Sleep Apnea**: Breathing pauses during sleep causing disruption

## 🔍 Methodology

### 1. Data Preprocessing

- **Missing Value Handling**: Replaced NaN values in Sleep Disorder column with 'None'
- **Feature Engineering**: Split blood pressure into systolic and diastolic components
- **Data Cleaning**: Standardized BMI categories and removed unnecessary columns
- **Label Encoding**: Converted categorical variables to numerical format

### 2. Exploratory Data Analysis

- **Demographic Analysis**: Gender and age distribution patterns
- **Occupational Impact**: Correlation between profession and sleep disorders
- **BMI Relationship**: Body mass index influence on sleep health
- **Correlation Analysis**: Feature relationships and importance

### 3. Machine Learning Models

Two classification algorithms were implemented and compared:

#### Decision Tree Classifier

- **Training Accuracy**: 93.5%
- **Test Accuracy**: 87%
- **F1-Score**: 0.83

#### Random Forest Classifier ⭐

- **Training Accuracy**: 93.5%
- **Test Accuracy**: 89%
- **F1-Score**: 0.86

## 📈 Key Findings

### Demographic Insights

- **Gender Differences**: Females show higher prevalence of Sleep Apnea, while males have more Insomnia cases
- **Age Distribution**: Majority of affected individuals are between 30-45 years

### Occupational Impact

- **High-Risk Professions**: Nurses and salespersons show highest sleep disorder rates
- **Low-Risk Professions**: Engineers, doctors, and accountants have minimal sleep issues

### Health Factors

- **BMI Correlation**: Overweight and obese individuals have significantly higher sleep disorder rates
- **Normal BMI**: Individuals with normal BMI show lowest sleep disorder prevalence

## 🛠️ Technologies Used

- **Python 3.8+**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib & Seaborn**: Data visualization
- **Scikit-learn**: Machine learning algorithms and evaluation

## 📁 Project Structure

```
Sleep Disorder Prediction/
├── Sleep Disorder Prediction.ipynb    # Main analysis notebook
├── Sleep_health_and_lifestyle_dataset.csv  # Dataset
├── description.md                      # This README file
└── Sleep Disorder Prediction.pdf       # Analysis report
```

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Running the Analysis

1. Clone this repository
2. Navigate to the project directory
3. Open the Jupyter notebook: `Sleep Disorder Prediction.ipynb`
4. Run cells sequentially to reproduce the analysis

## 📊 Model Performance

| Model         | Accuracy | Precision | Recall   | F1-Score |
| ------------- | -------- | --------- | -------- | -------- |
| Decision Tree | 87%      | 0.85      | 0.83     | 0.83     |
| Random Forest | **89%**  | **0.87**  | **0.85** | **0.86** |

## 🎯 Impact & Applications

This project provides valuable insights for:

- **Healthcare Providers**: Early identification of at-risk patients
- **Individuals**: Understanding personal sleep health factors
- **Researchers**: Foundation for further sleep disorder studies
- **Public Health**: Population-level sleep health interventions

## 🔮 Future Enhancements

- **Feature Expansion**: Include additional lifestyle factors
- **Model Optimization**: Hyperparameter tuning and advanced algorithms
- **Real-time Prediction**: Deploy as a web application
- **Longitudinal Analysis**: Track sleep patterns over time

## 📝 Conclusion

The analysis successfully identified key predictors of sleep disorders, with the Random Forest Classifier achieving 89% accuracy. The model demonstrates that gender, occupation, and BMI are significant factors in sleep disorder prediction, providing a reliable tool for early identification and intervention.

## 👤 Author

**Saif Eldeen** - Data Science Project - Sleep Disorder Prediction Analysis

📧 Email: [saif eldeenamr10@gmail.com](mailto:saif eldeenamr10@gmail.com)

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page and submit pull requests.

---

⭐ **If you find this project helpful, please give it a star!**
