Pumpkin Seeds Classification using Ensemble Machine Learning and MRMR

This project presents an "Innovative Ensemble Machine Learning Framework for Pumpkin Seed Classification using Forward Sequential MRMR (Minimum Redundancy Maximum Relevance)" feature engineering.

---

Project Overview

Pumpkin seeds of varieties "Ürgüp Sivrisi" and "Çerçevelik" were classified using ensemble learning models with feature selection techniques to boost accuracy and performance.

---

Techniques Used

- Feature Engineering: MRMR (Minimum Redundancy Maximum Relevance)
- Classifiers: Boosted Trees, Bagged Trees, RUS Boosted Trees, Optimizable Ensembles
- Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, Specificity

---

Dataset

- Total Samples: 2500 seeds
- Features:13 (e.g., Area, Perimeter, Solidity, Aspect Ratio)
- Classes:52% Çerçevelik, 48% Ürgüp Sivrisi

---

Key Results

| Model                | Accuracy (%) |
|----------------------|--------------|
| Boosted Trees        | 90.4%        |
| Bagged Trees         | 88.8%        |
| RUS Boosted Trees    | 89.6%        |
| Optimizable Ensemble | 91.0%        |

---

 Folder Structure

- `Dataset/` – Contains the CSV or .mat dataset
- `Results/` – Includes screenshots of graphs etc.
- `Documentation/` – Abstract, implementation, results, and conclusion

---

How to Reproduce the Project

This project was done using MATLAB GUI tools (no coding). You can reproduce the results by:

1. Importing the dataset into MATLAB
2. Opening Classification Learner App
3. Selecting MRMR for feature selection
4. Choosing and training ensemble classifiers
5. Exporting performance graphs and results

---

License

This project and its contents (including results and methodology) are protected under academic research rights.

No part of this work may be reused, copied, or published without explicit permission from the authors.

This repository is shared for academic review and demonstration purposes only. The associated research paper is not included here to prevent unauthorized use.

