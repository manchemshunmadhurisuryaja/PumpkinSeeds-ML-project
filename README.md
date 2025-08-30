# 🎃 **Pumpkin Seeds Classification using Ensemble Machine Learning & MRMR**

This project presents an **Innovative Ensemble Machine Learning Framework** for **Pumpkin Seed Classification** using **Forward Sequential MRMR (Minimum Redundancy Maximum Relevance)** feature engineering.

---

## 📌 **Project Overview**

We classified pumpkin seeds of two varieties:
✅ **Ürgüp Sivrisi**
✅ **Çerçevelik**

The goal was to **boost accuracy and performance** using **ensemble learning models** combined with **feature selection**.

---

## 🔍 **Process Workflow**

1️⃣ **Data Split**:

* 70% → Training
* 10% → Hold-out Validation
* 20% → Testing

2️⃣ **Feature Selection**:

* Applied **MRMR** to select **top relevant features**
* Found that **8 features** are optimal (accuracy drops after 6, so 8 is the sweet spot)

3️⃣ **Model Training & Testing**:

* Trained multiple **ensemble models**
* Compared performance using **evaluation metrics**

4️⃣ **Best Model**:
⭐ **Optimizable Ensemble** achieved the **highest accuracy**

---

## 🛠 **Techniques Used**

* **Feature Engineering**: MRMR (Minimum Redundancy Maximum Relevance)

* **Classifiers**:
  ✅ Boosted Trees
  ✅ Bagged Trees
  ✅ RUS Boosted Trees
  ✅ Optimizable Ensemble

* **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, Specificity

---

## 📊 **Dataset**

* **Samples**: 2,500 pumpkin seeds
* **Features**: 13 (e.g., Area, Perimeter, Solidity, Aspect Ratio)
* **Classes**:

  * 52% Çerçevelik
  * 48% Ürgüp Sivrisi

---

## ✅ **Key Results**

| 🏆 **Model**                | **Accuracy (%)** |
| --------------------------- | ---------------- |
| 🔸 Boosted Trees            | 90.4%            |
| 🔸 Bagged Trees             | 88.8%            |
| 🔸 RUS Boosted Trees        | 89.6%            |
| 🌟 **Optimizable Ensemble** | **90.8%**        |

---

## 📂 **Folder Structure**

* 📁 `Dataset/` → Contains CSV or .mat dataset
* 📁 `Results/` → Performance graphs & screenshots
* 📁 `Documentation/` → Abstract, implementation, results, and conclusion

---

## 🖥 **How to Reproduce**

1. Open **MATLAB**
2. Import the **dataset**
3. Use **Classification Learner App**
4. Apply **MRMR feature selection**
5. Train using **Ensemble models**
6. Evaluate and **export results**

---

## 🔐 **License**

This work is for **academic review & demonstration**.
No part may be reused, copied, or published without **explicit permission** from the authors.

