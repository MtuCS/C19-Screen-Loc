# Suggested public GitHub layout for this paper

## 1. Minimum public release
Use this if you want the repo to look professional even before uploading full code.

- `README.md`
- `assets/pipeline_overview.png`
- `docs/paper_summary.md`
- `docs/dataset_notes.md`
- `docs/results_summary.md`
- `.gitignore`
- `requirements.txt`

## 2. Better research release
Add these when your code is ready:

- `scripts/train_classification.py`
- `scripts/train_localization.py`
- `scripts/infer_pipeline.py`
- `src/classification/models.py`
- `src/classification/dataset.py`
- `src/classification/train.py`
- `src/classification/evaluate.py`
- `src/localization/train_yolo.py`
- `src/localization/predict_yolo.py`
- `src/localization/convert_siim_to_yolo.py`
- `configs/classification.yaml`
- `configs/localization.yaml`

## 3. Nice extras
- `demo/app.py`
- `LICENSE`
- `.github/ISSUE_TEMPLATE/`
- `.github/workflows/ci.yml`
- release notes with checkpoints
