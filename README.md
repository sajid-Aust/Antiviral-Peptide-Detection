# An Ensemble Approach towards Effective Vaccine Candidates Identification Against Different Types of Viruses

## Project Overview

This project focuses on detecting antiviral peptides (AVPs) using peptide sequences and associated characteristics. AVPs are a promising approach to combat viral infections due to their targeted mechanisms. This research creates a specialized dataset for viral peptides and applies ensemble machine learning techniques to detect antiviral peptides (AVPs) based on peptide sequences and associated characteristics. By leveraging various computational tools, essential peptide properties were extracted, enabling the use of advanced ensemble classifiers to identify peptides with potential antiviral properties.


## Dataset

The dataset consists of labeled peptide sequences and various characteristics of each sequence. These characteristics were extracted using computational tools:

- **Expasy**: Theoretical pI, extinction coefficient, molecular weight, half-life, instability index, aliphatic index, and GRAVY.
- **APD3 Tool**: Hydrophobic residue, net charge, and Boman Index.
- **VaxiJen Tool**: Protective antigenic score.
- **AllerCatPro 2.0**: Allergenicity.

## Code Workflow

1. **Data Preprocessing**: Filled missing values, encoded sequences, and balanced the dataset with SMOTE.
2. **Model Training**: Trained classifiers (SVM, Random Forest, AdaBoost, XGBoost, etc.) and ensemble methods (Voting, Stacking).
3. **Evaluation**: Calculated metrics like accuracy, F1 score, and ROC-AUC; saved confusion matrices and ROC curves.

