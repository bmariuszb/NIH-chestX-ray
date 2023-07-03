# NIH ChestX-ray

## Dataset
ChestX-ray14 contains 112,120 X-ray image scans of 30,805 unique individuals.

Labels
<ol start="0">
  <li>No Finding</li>
  <li>Hernia</li>
  <li>Emphysema</li>
  <li>Nodule</li>
  <li>Pneumonia</li>
  <li>Consolidation</li>
  <li>Cardiomegaly</li>
  <li>Effusion</li>
  <li>Mass</li>
  <li>Pleural_Thickening</li>
  <li>Atelectasis</li>
  <li>Pneumothorax</li>
  <li>Fibrosis</li>
  <li>Infiltration</li>
  <li>Edema</li>
</ol>


Each image can have multiple labels.

## Goal of the project
Use your own neural network and 3-4 pretrained networks to classify these images.
Compare the metrics with those existing in the literature.

Models
- Custom
- VGG16
- Densenet121
- Resnet50

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

## How to run in Google Colab
To train models use scripts from Train directory, add selected script *.ipynb file to google colab, adjust the paths according to your setup.

## How to calculate metrics in Google Colab
Copy selected *.pt file from Models to Models directory on Google Drive, adjust paths in scripts from Metrics directory.

## Documentation [PL]

[Presentation](https://docs.google.com/presentation/d/18sR3KB3gY4Yhe0k80pLE8e4L-01S1Fz5_S2odM_nUeE/edit#slide=id.g256cf2b4612_0_75) \
[Report](https://docs.google.com/document/d/1hezKeDe7nuQUc5aHKRLeVLIDudnaqKnJPTbB35y-12E/edit)
