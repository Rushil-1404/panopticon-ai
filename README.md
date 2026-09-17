# Panopticon AI

Panopticon AI is an intelligent proctoring project focused on identifying likely cheating behavior from time-series telemetry while minimizing false accusations.

## Repository Contents

- `AI_Student_code_completed.ipynb` — main notebook containing data preparation, feature engineering, model training, and evaluation.
- `system_events.csv` — system event telemetry source data.
- `video_telemetry.csv` — video telemetry source data.

## Project Highlights

- Aligns mismatched telemetry streams with temporal joins.
- Handles dropped frames with imputation.
- Uses rolling-window features to reduce noise sensitivity.
- Trains classification models with a strict precision-oriented decision threshold.

## Getting Started

1. Open `AI_Student_code_completed.ipynb` in Jupyter Notebook or VS Code.
2. Ensure Python dependencies used in the notebook are installed (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`).
3. Run notebook cells in order to reproduce training and evaluation.
