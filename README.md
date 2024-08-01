# DDoS Attack Detection Model using Decision Tree and Random Forest

This project demonstrates the creation of a hybrid model to detect DDoS (Distributed Denial of Service) attacks using Decision Tree and Random Forest algorithms. The NSL-KDD dataset is used for training and testing the models.

## Project Overview

The primary goal of this project is to efficiently detect and manage potential DDoS attacks across connected systems on a network. The project leverages machine learning models, specifically Random Forest and Decision Tree classifiers, to identify and prevent DDoS attacks.

## Objectives

- Enhance network security by developing a robust and accurate detection system for DDoS attacks.
- Leverage the complementary strengths of Random Forest and Decision Tree classifiers to improve detection accuracy and resilience.
- Process and analyze network traffic data to identify and classify potential DDoS attacks.

## Architecture

The detection system follows a comprehensive workflow:
1. Collecting traffic data.
2. Organizing data.
3. Predicting patterns.
4. Identifying attacks.
5. Preprocessing features.
6. Classifying attacks.
7. Continuous monitoring using a checker process.

This architecture ensures that network traffic data undergoes a thorough analysis to differentiate between normal activity and potential DDoS attacks.

## Implementation

### Libraries and Tools
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Requests
- Gzip

### Steps

1. **Data Loading**: Load the NSL-KDD dataset.
2. **Preprocessing**: 
   - Handle missing values.
   - Normalize numerical variables.
   - Convert categorical attributes to numerical equivalents using one-hot encoding.
3. **Model Training**:
   - Train a Decision Tree classifier.
   - Train a Random Forest classifier.
4. **Evaluation**:
   - Evaluate the models using metrics like accuracy, precision, recall, and F1 score.
   - Visualize the performance with confusion matrices, ROC curves, and precision-recall curves.

### Results

- Both the Decision Tree and Random Forest classifiers were trained and evaluated.
- Random Forest showed a slight edge in performance metrics.

## Visualizations

- **Class Distribution**: Distribution of different types of attacks in the dataset.
- **Feature Importance**: Important features identified by the Random Forest classifier.
- **Confusion Matrix**: Confusion matrices for both classifiers.
- **ROC Curve**: ROC curves for both classifiers.
- **Precision-Recall Curve**: Precision-recall curves for both classifiers.

## Significance and Future Work

This project contributes to the field of cybersecurity by demonstrating the application of machine learning in detecting DDoS attacks. The hybrid model shows promise for improving DDoS detection systems, with potential applications in cloud-based DDoS mitigation.

Future work could involve exploring other machine learning models to further enhance detection accuracy and resilience.

## How to Run

1. Clone the repository.
2. Install the required libraries:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn requests
   ```
3. Run the Jupyter notebook or Python script containing the project code.

## Conclusion

This project successfully developed a hybrid model to detect DDoS attacks using Decision Tree and Random Forest classifiers. The implementation and results demonstrate the potential of machine learning in enhancing network security.
