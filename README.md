# INT3405E2-CAFA-6-Protein-Function-Prediction

## Competition: [here](https://www.kaggle.com/competitions/cafa-6-protein-function-prediction/)

## Score: 0.262. 

## Rank: 357/1005 on 2025-12-09.

## Member
- Nguyen Lam Thai
- Nguyen Cong Tuan Phuong

## Report: [here](report.pdf)

## Naming convention for notebooks

| In report | In GitHub |
|----------|----------|
| Model #0  |  kaggle-notebook/2025-11-30_cafa6-00-baseline.ipynb |
| Model #1  |  kaggle-notebook/2025-12-01_cafa6-01-enhanced-feature-extraction.ipynb |
| Model #2  |  kaggle-notebook/2025-12-02_cafa6-02-enhanced-feature-extraction.ipynb |
| Model #3  |  kaggle-notebook/2025-12-04-cafa6-03-enhanced-feature-extraction.ipynb |
| Model #4  | kaggle-notebook/2025-12-05-cafa6-07-model-improvement-V1.ipynb  |
| Model #5  | kaggle-notebook/2025-12-05-cafa6-07-model-improvement-V2.ipynb  |
| Model #6  | kaggle-notebook/2025-12-05-cafa6-08-model-improvement-V1.ipynb  |
| Model #7  | kaggle-notebook/2025-12-05-cafa6-08-model-improvement-V3.ipynb  |
| Model #8  | kaggle-notebook/2025-12-08-cafa6-11-model-ensemble-V1.ipynb  |
| Model #9  | kaggle-notebook/2025-12-07-cafa6-09-model-ensemble.ipynb  |

## How to reproduce 0.262?
- git clone this repo
- extract [ESM2.7z](ESM2.7z) to ESM2/
- Run [kaggle-notebook/2025-12-05-cafa6-08-model-improvement-V3.ipynb](kaggle-notebook/2025-12-05-cafa6-08-model-improvement-V3.ipynb). Remember to change `ESM_EMBEDDINGS = "/kaggle/input/esm2-t6-8m-ur50d-cafa6"` to `ESM_EMBEDDINGS = "ESM2"` first.
- submit to CAFA6

## Submission file: [here](submission.7z)

## Note
- The report doesn't show all submissions. So some notebooks in [kaggle-notebook/](kaggle-notebook) are not referenced in the table above.
- Refer to those notebooks for more information.
