# Automating-Multi-Region-Temporal-EquiFACS-Annotation-for-Equine-Pain-Recognitions

# Nostrils-Based Equine Pain Detection (YOLO + SAM2 + RIFE + I3D)

This repository contains the full implementation of a modular deep-learning pipeline
for automated nostril-based pain detection.

## Models Used
- YOLOv8 — nostril localization
- SAM2 — nostril segmentation
- RIFE v4 — frame interpolation (50 FPS)
- I3D — pain classification (mild / moderate)

## Dataset
12 equine videos labeled using CVAT (nostril region).

## Pipeline
1. Frame extraction
2. YOLO detection
3. SAM2 mask refinement
4. RIFE interpolation
5. I3D classification

## Results
- Accuracy: 87.4%
- F1-score: 0.87
- AUC: 0.90

## Citation
IEEE-format citations provided in final report.
