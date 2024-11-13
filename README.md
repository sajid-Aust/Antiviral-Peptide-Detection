# An Ensemble Approach towards Effective Vaccine Candidates Identification Against Different Types of Viruses

## Project Overview

This project focuses on detecting antiviral peptides (AVPs) using peptide sequences and associated characteristics. AVPs are a promising approach to combat viral infections due to their targeted mechanisms. This research creates a specialized dataset for viral peptides and applies ensemble machine learning techniques to detect antiviral peptides (AVPs) based on peptide sequences and associated characteristics. By leveraging various computational tools, essential peptide properties were extracted, enabling the use of advanced ensemble classifiers to identify peptides with potential antiviral properties.


## Dataset

The dataset consists of peptide sequences along with their various properties, providing a comprehensive foundation for antiviral peptide (AVP) detection. Each peptide sequence is annotated with properties including molecular weight, theoretical pI, extinction coefficient, half-life (hours), instability index, aliphatic index, GRAVY (Grand Average of Hydropathicity), hydrophobic residue count, net charge, Boman Index (Kcal/mol), protective antigenic score, and allergenicity. These attributes were derived using computational Web tools, allowing for an enriched dataset.

## Code Workflow

1. **Data Preprocessing**: Filled missing values, encoded sequences, and balanced the dataset with SMOTE.
2. **Model Training**: Trained classifiers (SVM, Random Forest, AdaBoost, XGBoost, etc.) and ensemble methods (Voting, Stacking).
3. **Evaluation**: Calculated metrics like accuracy, F1 score, and ROC-AUC; saved confusion matrices and ROC curves.

## Acknowledgments

- [Expasy](https://web.expasy.org/protparam/)
- [APD3 Tool](https://aps.unmc.edu/prediction)
- [VaxiJen Tool](https://www.ddg-pharmfac.net/vaxijen/VaxiJen/VaxiJen.html)
- [AllerCatPro 2.0](https://allercatpro.bii.a-star.edu.sg/allergy/index.html)


