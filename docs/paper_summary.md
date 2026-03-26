# Paper summary

This work proposes a two-stage framework for chest X-ray based COVID-19 support:

1. **Stage 1:** binary classification (COVID vs Non-COVID)
2. **Stage 2:** lesion localization for samples predicted as COVID

## Why this design?
A single classifier can achieve strong discrimination, but clinicians also benefit from lesion localization. Instead of relying only on Grad-CAM, this framework forwards likely COVID cases to a dedicated object detector.

## Main takeaways
- DenseNet-121 is the strongest classifier among tested backbones.
- YOLOv12x is the strongest tested detector, but localization remains the bottleneck.
- The method is modular and easy to extend to other thoracic disease screening settings.
