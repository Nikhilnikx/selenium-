# Horror Roller Coaster Age Detection

Detects age & gender from images for roller coaster entry approval:
- Age < 13 or > 60: "Not allowed" (red rectangle)
- Stores age, gender, entry time in Excel/CSV.

## Files
- `requirements.txt`: Dependencies
- `model_training.ipynb`: Training & evaluation code
- `saved_model/`: Model weights
- `output/entry_log.csv`: Entry log
- `gui_app.py`: Optional GUI

## Large Files
- [Google Drive Link to Model Weights](https://drive.google.com/your-model-link)
- [Google Drive Link to Saved Model](https://drive.google.com/your-model-link)

## Usage
1. Install requirements: `pip install -r requirements.txt`
2. Run notebook for training/evaluation
3. Run GUI (optional): `streamlit run gui_app.py`
4. Entry logs saved in `output/entry_log.csv`

## Metrics
- Accuracy: 71%
- Confusion matrix, precision, recall: See `metrics_report.md`