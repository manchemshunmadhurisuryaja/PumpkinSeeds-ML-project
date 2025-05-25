Dataset Description:

2500 rows, 13 columns (12 numeric features + 1 categorical label)

Classes: Çerçevelik (52%), Ürgüp Sivrisi (48%)

Preprocessing Steps:

1.Handling missing values

2.Discretization of continuous variables

3.Normalization (0 to 1 scale)

4.Outlier detection and removal

5.Elimination of irrelevant data

Feature Engineering:

MRMR (Minimum Redundancy Maximum Relevance)

Top features: Aspect Ratio, Equiv Diameter, Solidity, Extent

Others: Major Axis Length, Minor Axis Length, Roundness, Compactness, etc.

Models Used:

1.Boosted Trees: Weights updated based on misclassifications

2.Bagged Trees: Bootstrap aggregating (random subsets)

3.RUS Boosted Trees: Random under-sampling + boosting

4.Optimizable Ensemble:Uses grid search and cross-validation for best performance