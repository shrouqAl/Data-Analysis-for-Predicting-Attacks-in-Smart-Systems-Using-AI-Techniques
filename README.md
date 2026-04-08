# Data Analysis for Predicting Attacks in Smart Systems Using AI Techniques

## 📌 Overview
This repository contains the code and machine learning models developed for the IEEE published research paper: **"Data Analysis for Predicting Attacks in Smart Systems Using AI Techniques"**. 

The project proposes an AI-driven framework to predict and mitigate Distributed Denial of Service (DDoS) attacks in smart city infrastructures using advanced Machine Learning (ML) and Deep Learning (DL) algorithms.

## 📊 Dataset
The models were trained and evaluated using the **UNSW-NB15** dataset, a highly respected and comprehensive dataset used for network intrusion detection and cybersecurity research. 

## 🛠️ Technologies & Libraries Used
* **Language:** Python
* **Data Processing:** Pandas, NumPy, StandardScaler
* **Machine Learning:** Scikit-Learn (Decision Tree, Logistic Regression, KNN)
* **Deep Learning:** TensorFlow / Keras (CNN, SimpleRNN, LSTM, GRU)

## 🧠 Methodology & Models
1. **Data Preprocessing:** Handled missing values, normalized numerical features using Min-Max scaling and Z-score standardization, and addressed class imbalances.
2. **Machine Learning Models:** Implemented and optimized algorithms. The **Decision Tree** model was fine-tuned using `GridSearchCV` to achieve optimal performance.
3. **Deep Learning Models:** Developed sequence models (RNN, LSTM, GRU) and CNNs, enhanced with advanced optimization callbacks like `EarlyStopping` and `ReduceLROnPlateau`.

## 🚀 Key Results
* The optimized **Decision Tree** algorithm achieved an outstanding accuracy of **92.36%** and an F1-Score of **0.929**, significantly outperforming baseline models like Logistic Regression.
* Deep Learning models demonstrated high operational efficiency and stability for sequential data tasks, with SimpleRNN showing the highest improvement post-optimization.

## 🔗 Publication
This project has been published in IEEE. You can read the full research paper here:
**[View Paper on IEEE Xplore](https://doi.org/10.1109/ICCIT63348.2025.10989284)**
