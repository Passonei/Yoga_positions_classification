# Yoga_positions_classification
Kaggle task classification of yoga postures (https://www.kaggle.com/datasets/tr1gg3rtrash/yoga-posture-dataset).

In this task, authors of other notebooks use CNNs and transfer learning to checkout individual yoga poses. I approached this task differently and used pose estimation to extract new features describing the position of body points. 33 points are extracted, each of which is described by 4 values (3 position coordinates and visibility). Random Forest is then used for classification. After additional application of SMOTE, the accuracy of the model is ~96%.
