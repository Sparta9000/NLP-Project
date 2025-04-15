# Mental Health Meme Classifier - Inference Notebooks

This repository contains Jupyter notebooks for performing inference on mental health memes using pretrained models. The classification is divided into two tasks:

- `trained_anxiety.ipynb`: Classifies memes into one of several anxiety categories (single-label classification).
- `trained_depression.ipynb`: Predicts multiple subcategories of depression (multi-label classification).

Both notebooks use pretrained multimodal models that combine visual and textual meme features.

## Requirements

To run the notebooks, install the following Python libraries:

```bash
pip install pandas numpy matplotlib scikit-learn jupyter transformers torch torchvision tqdm pillow
```

## Getting Started

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks and run cells sequentially (Make sure to change any paths to set your own dataset)

## Model Pre-Trained Weights

You can download the pre-trained model weights from the links below:

- [Anxiety Model Weights](https://drive.google.com/file/d/16mIkJvgao_jahdWoyE-FD5NDste2pY34/view?usp=sharing)
- [Depression Model Weights](https://drive.google.com/file/d/1WGVLdLLJmz5aRu7Xj175sIul4ViqA6Dp/view?usp=sharing)

## Author(s)

- Manan Aggarwal (2022273)
- Shobhit Raj (2022482)
- Souparno Ghose (2022506)

---
