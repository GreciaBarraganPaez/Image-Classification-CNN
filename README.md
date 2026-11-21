# CIFAR-10 Image Classification with a Convolutional Neural Network

An educational computer vision project developed during my **Artificial Intelligence diploma**. I implemented and trained a convolutional neural network (CNN) in **PyTorch** to classify the ten object categories in [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html).

## Visual overview


*Conceptual architecture illustration, not a screenshot of model predictions.* The notebook contains prediction visualizations; actual screenshots can be added to `images/` when exported from a verified run.


## Project overview
- **Task:** Multi-class classification (ten CIFAR-10 categories).
- **Architecture:** Three convolutional layers (32, 64, 128 channels), max pooling and fully connected layers.
- **Training:** Adam optimizer, cross-entropy loss, ten epochs.
- **Dataset:** CIFAR-10, downloaded automatically by torchvision.
- **Historical notebook result:** 77.29% test accuracy, **not independently reproduced** for this publication.

## Files
- `CIFAR10_CNN_Classification.ipynb`: Training, evaluation and visualization of predictions.
- `requirements.txt`: Dependencies.

**Note:** The original trained checkpoint (`modelo_cifar10.pth`, ~2.4 MB) is available in the accompanying local project archive but is not yet uploaded through the GitHub integration. You can retrain and save a checkpoint by running the notebook. The dataset is excluded from GitHub.

## Run
```bash
python -m venv .venv
pip install -r requirements.txt
jupyter notebook CIFAR10_CNN_Classification.ipynb
```

The original notebook used random augmentation on the test set; the publication copy makes test preprocessing deterministic. The historical 77.29% score refers to the earlier experiment, not the corrected evaluation. Coursework prototype, not a deployed system.

## Skills
Python · PyTorch · CNN · Computer Vision · Model Training · Evaluation


## Experimental images

No experimentally verified images are included yet. Real code outputs (or photographs of the actual hardware for Arduino) will be added when available. Conceptual diagrams are not presented as measured results.
