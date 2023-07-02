# NIH ChestX-ray

## Dataset
ChestX-ray14 contains 112,120 X-ray image scans of 30,805 unique individuals.

Labels
0. No Finding
1. Hernia
2. Emphysema
3. Nodule
4. Pneumonia
5. Consolidation
6. Cardiomegaly
7. Effusion
8. Mass
9. Pleural_Thickening
10. Atelectasis
11. Pneumothorax
12. Fibrosis
13. Infiltration
14. Edema

Each image can have multiple labels.

## Goal of the project
Use your own neural network and 3-4 pretrained networks to classify these images.
Compare the metrics with those existing in the literature.

Metrics
- MSE(Mean Squared Error)
- MSE for each label
- AUC-ROC(Area Under the Receiver Operating Characteristic Curve)
- Confusion Matrix for each label
- Specificity(true negative rate):
- Sensitivity(true positive rate or recall)
- Validation Accuracy for different thresholds
- F1 Score(harmonic mean of precision and recall)
- Precision(proportion of true positive predictions out of the total predicted positives)
- Hamming Loss
- Jaccard Index(also known as intersection over union)
- Exact Match(Accuracy Exact Match)

Models
- Custom
- VGG16
- Densenet121
- Resnet50

[Presentation](https://docs.google.com/presentation/d/18sR3KB3gY4Yhe0k80pLE8e4L-01S1Fz5_S2odM_nUeE/edit#slide=id.g256cf2b4612_0_75) \
[Report](https://docs.google.com/document/d/1hezKeDe7nuQUc5aHKRLeVLIDudnaqKnJPTbB35y-12E/edit)
