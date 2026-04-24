## Histopathology tumor classifier
A (simple) machine learning model for classifying tumor vs normal in H&amp;E lymph node biopsies. 

## Basic overview
- **Task**: Binary classification (Normal vs. Tumor)
- **Dataset**: PatchCamelyon (96x96 RGB patches)
- **Model**: Transfer Learning with MobileNetV2
- **Accuracy**: 91,7%

## Results
| Metric    | Score  |
|-----------|--------|
| Accuracy  | 0.91   |
| Precision | 0.92   |
| Recall    | 0.92   |
| F1-Score  | 92.0   |
| AUC-ROC   | 0.98   |

## How to Run

```bash
# Clone repository
git clone https://github.com/karpondeeros/tumor-classifier-1

# Install dependencies
pip install -r requirements.txt

# Open notebook in Google Colab
# Upload notebook.ipynb and run all cells
```

## Requirements

- tensorflow =2.10.0
- numpy =1.21.0
- matplotlib =3.5.0
- scikit-learn =1.0.0
- h5py =3.7.0
- pillow =9.0.0
- seaborn =0.11.0

## Acknowledgments

- Dataset: [PatchCamelyon](https://github.com/basveeling/pcam)
- Inspired by Camelyon16 Challenge
- Support from Calude AI (Sonnet 4.5)
