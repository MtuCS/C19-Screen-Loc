# Results summary

## Classification
DenseNet-121 achieved the best overall results:
- Accuracy: 99.0%
- Sensitivity: 96.4%
- Specificity: 99.4%
- AUC: 0.9961
- Precision: 0.9926

## External checks
- Hold-out in stratified 5-fold setting: 98.02% accuracy
- Patients Lungs: 96.94% accuracy
- COVID CXR Small: 95.78% accuracy

## Localization
YOLOv12x achieved:
- mAP@0.5: 0.449
- mAP@0.5:0.95: 0.174
- Precision: 0.511
- Recall: 0.437

## Interpretation
The paper shows a strong classification stage and a weaker but useful localization stage. The detector is the main area for future improvement.
