# Enhancing Depression Prediction through Data-Driven Methods

Depression is a widespread mental health issue requiring precise and timely predictions for effective treatment. This project presents a hybrid model combining Support Vector Machine (SVM) and Convolutional Neural Networks (CNNs). We evaluate the models with and without Synthetic Minority Over-sampling Technique (SMOTE) to address risks in medical datasets.

## Dataset Used

[Dataset](https://github.com/Sabab31/Depression-Repository/blob/main/Depression%20Dataset.csv)

## Contributers

- **Alphonsa Jose**  
  Email: [BL.EN.U4CSE21013@bl.students.amrita.edu](mailto:BL.EN.U4CSE21013@bl.students.amrita.edu)

- **Achal Baniya**  
  Email: [BL.EN.U4CSE21005@bl.students.amrita.edu](mailto:BL.EN.U4CSE21005@bl.students.amrita.edu)

- **Angelina George**  
  Email: [BL.EN.U4CSE21017@bl.students.amrita.edu](mailto:BL.EN.U4CSE21017@bl.students.amrita.edu)

- **Dr. K Dinesh Kumar**  
  Email: [kk_dinesh@blr.amrita.edu](mailto:kk_dinesh@blr.amrita.edu)

## Results

### Table 1. Showcasing different accuracies obtained for Dataset with SMOTE  
*30 Features [Excluding Target feature "DEPRESSED"] - With SMOTE*

| S.No. | Models                     | Accuracy | Class | Precision | Recall | F1 Score |
|-------|-----------------------------|----------|-------|-----------|--------|----------|
| 4     | Support Vector Machine       | 0.92453  | 0     | 0.99      | 0.88   | 0.93     |
|       |                             |          | 1     | 0.86      | 0.99   | 0.92     |
| 6     | k-Nearest Neighbours         | 0.89308  | 0     | 0.84      | 1.00   | 0.91     |
|       |                             |          | 1     | 1.00      | 0.75   | 0.86     |
| 9     | eXtreme Gradient Boosting    | 0.86164  | 0     | 0.92      | 0.84   | 0.87     |
|       |                             |          | 1     | 0.80      | 0.90   | 0.85     |

### Table 2. Showcasing accuracy obtained with SMOTE using the proposed Hybrid Model  
*With SMOTE*

| Models        | Precision (0) | Precision (1) | F1-Score (0) | F1-Score (1) | Recall (0) | Recall (1) | Train Accuracy | Test Accuracy | Time(s) |
|---------------|---------------|---------------|--------------|--------------|------------|------------|----------------|---------------|---------|
| CNN + SVC     | 0.94          | 0.91          | 0.94         | 0.92         | 0.93       | 0.93       | 0.929          | 0.930         | 2.3     |


The hybrid model, which combines Convolutional Neural Networks (CNN) and Support Vector Machine (SVM) with SMOTE augmentation, achieved a remarkable test accuracy of **93%**. In comparison, the model without SMOTE achieved **88.4%** accuracy. These findings underscore the efficacy of the hybrid model and emphasize the importance of addressing class imbalance in medical datasets to enhance prediction accuracy.
