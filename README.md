# F.A.K.E.D.

Deep learning experiments for deepfake detection and manipulation localization using FaceForensics++ video data.

## Notebooks

| Notebook | Description |
| --- | --- |
| `notebooks/f-a-k-e-d-v2 (1).ipynb` | Version 2 experiment notebook. |
| `notebooks/fakedModifiedCodeR2(2).ipynb` | Modified review-2 experiment. |
| `notebooks/Version 2 of F.A.K.E.D(2).ipynb` | Version 2 variant with LeakyReLU configuration. |
| `notebooks/fakedv3.ipynb` | Extended experiment notebook with ResNet18, EfficientNet-B0 and MobileNetV3-Large encoders, U-Net and attention U-Net variants, evaluation and report exports. |

The uploaded notebooks retain their original code, metadata and saved outputs. Each notebook has its own configuration; inspect it before running.

## Running

1. Open a notebook in Kaggle or Jupyter. A CUDA GPU is recommended for training.
2. Obtain the FaceForensics++ dataset separately under its applicable access terms. The dataset is not included here.
3. On Kaggle, attach the dataset under `/kaggle/input`. For a local run, update `CANDIDATE_DATA_ROOTS` to your dataset location.
4. Install the imported packages: PyTorch, torchvision, OpenCV, NumPy, pandas, matplotlib, seaborn, scikit-learn, tqdm and IPython.
5. Review the data paths, sample limits, model settings and time budgets, then run cells in order.


