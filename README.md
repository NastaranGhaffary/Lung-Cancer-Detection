# Binary Classification (Benign vs. Malignant) and 5-Class Classification (Stages 1-5) of Lung Cancer Using AI on CT Images
## Abstract
This project presents an approach to a classification problem aimed at diagnosing lung cancer using CT images. Lung cancer is the leading cause of cancer-related deaths worldwide, accounting for 18% of total cancer fatalities in 2020. Due to its frequent late-stage diagnosis, survival rates remain low. To address this, screening programs have been developed, increasing the demand for accurate malignant nodule detection.

Lung tumors are typically assigned a malignancy score from 1 to 5, with higher scores indicating greater severity. Tumors classified as 1, 2, or 3 are considered "benign," while those in classes 4 and 5 are deemed "malignant." 
For the classification, both full size images and zoomed nodule images were available. <img width="834" alt="image" src="https://github.com/user-attachments/assets/a03f5569-0aab-4fa5-b287-6f96d78601f9" />

Therefore, there exists 4 classifiers in total: Binary Classifier for Full Images + 5-Class Classifier for Full Images + Binary Classifier for Nodule Images + 5-Class Classifier for Nodule Images. 


All the used framewrok regarding the preprocessing steps, the construction steps of classifiers using neural networks, the explainability and feature engineering steps are explained in the Classification_of_Lung_Tumors.pdf file.
