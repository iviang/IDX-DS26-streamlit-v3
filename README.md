# IDX-DS26-streamlit-v3
This is the version 3 of the streamlit task of the CA-Price-Prediction DS26 project.
Note: instead of relying on one model, switches between the top two models (LGBM-log, Ensemble stack-ridge). LGBM-log covers the luxury tail while Ensemble is better for mid-market typical home prediction. NOT a blend which was experimented via Ensemble stack4 in `06_evaluation.ipynb`
- Primary Model: Ensemble stack-ridge
- Secondary Model: LGBM-log
- Uses:
  - `models.pkl` (different from model.pkl in previous iterations)
  - updated `Requirements.txt`
- Changes Include:
  - Router switching between models instead of using one
  - now builds two representations per prediction
V3 Deployment visible at: <https://idx-ds26-app-v3-o8iv5baqvzgg2rb99jfviw.streamlit.app/>
