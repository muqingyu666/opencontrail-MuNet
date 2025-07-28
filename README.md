# opencontrail-MuNet

This repository hosts our experimental project for identifying contrails in satellite imagery. Our primary focus is on testing and validating deep learning methodologies for semantic segmentation, particularly in scenarios with significant class imbalance and the challenge of detecting very small objects.

This work is inspired by the Kaggle competition "Google Research - Identify Contrails to Reduce Global Warming". We aim to explore innovative modeling techniques to contribute to this important field of climate science.

For more context on the problem, please visit the competition page:
[Google Research - Identify Contrails to Reduce Global Warming](https://www.kaggle.com/competitions/google-research-identify-contrails-reduce-global-warming/overview)


## Project Structure

Here is the proposed structure for this project, I host my raw data and pre-procesed data elsewhere because my disk space is runnning low:

```
.
├── README.md
├── requirements.txt         # Project dependencies
├── src/                     # Source code
│   ├── config.py            # Configuration settings
│   ├── dataset.py           # PyTorch Dataset and DataLoader classes
│   ├── model.py             # Model architecture
│   ├── train.py             # Main training script
│   ├── evaluate.py          # Script for evaluation and inference
│   └── utils.py             # Utility functions
├── notebooks/               # Notebooks for exploration and visualization
│   └── EDA.ipynb
└── saved_models/            # Saved model checkpoints and training history
    └── best_model.pth
```

## Contact Information
You are more than welcome to work with my little project, just have fun!
If you think I'm infringing, please contact me and I'll remove the infringing code or files.

Contact Info: muqy20@lzu.edu.cn 