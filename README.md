# **Machine Learning for Intrusion Detection Using CIC-IDS2017**

## **Overview**
This project focuses on enhancing Intrusion Detection Systems (IDS) using advanced Machine Learning (ML) and Deep Learning (DL) techniques. Leveraging the CIC-IDS2017 dataset, the study implements Multilayer Perceptrons (MLPs) for both binary and multiclass classification of network traffic. The models achieve state-of-the-art accuracy by employing XGBoost for feature selection and SMOTE for handling class imbalance.

---

## **Key Features**
- **Binary Classification:** Differentiates between benign and malicious traffic with up to 98.77% accuracy.
- **Multiclass Classification:** Identifies multiple attack types with 93.00% accuracy.
- **Feature Selection:** Uses XGBoost to reduce dimensionality and improve efficiency.
- **Class Imbalance Handling:** Applies SMOTE for improved detection of minority attack classes.
- **Optimized Architectures:** Five MLP models designed for scalability and resource optimization.

---

## **Dataset**
- **Name:** CIC-IDS2017  
- **Content:** Real-world traffic, including benign and updated attack types such as brute force, DDoS, and botnet attacks.  
- **Features:** 80 network traffic features extracted using CICFlowMeter.  
- **Preprocessing:** Cleaned, balanced, and split into training (75%), validation (10%), and testing (15%).

---

## **Technologies Used**
- **Programming Language:** Python  
- **Libraries & Tools:**
  - TensorFlow/Keras (Deep Learning)
  - XGBoost (Feature Selection)
  - SMOTE (Class Balancing)
  - Pandas & NumPy (Data Processing)
  - Matplotlib/Seaborn (Visualization)

---

## **Contributors**
- [**Ruturaj Jayant Kotwal**](mailto:ruturaj.kotwal@hof-university.de)  
  MSc Artificial Intelligence and Robotics  
  Hof University of Applied Sciences, Germany  

- [**Advait Santosh Lanjekar**](mailto:advait.lanjekar@hof-university.de)  
  MSc Artificial Intelligence and Robotics  
  Hof University of Applied Sciences, Germany  