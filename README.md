# Teeth Cavity Detection

> A deep learning-based image classification project for detecting dental caries from direct photographed images using VGG16 and other models.

---

## 🚀 Features

- Caries vs. No-Caries classification from dental X-ray images
- Preprocessing with `ImageDataGenerator`
- CNN-based models including VGG16
- Integration with Weights & Biases (wandb) for experiment tracking
- Visual model architecture rendering with `visualkeras`
- Dataset converted to CSV for scalable pipeline

---

## 🗂️ Dataset

Images are organized into `train` and `test` folders with subfolders:
```

teeth\_dataset/
├── train/
│   ├── caries/
│   └── no-caries/
├── test/
│   ├── caries/
│   └── no-caries/

````

CSV files are generated with image paths and binary labels:
- `0`: Caries
- `1`: No-Caries

---

## 📦 Installation

```bash
pip install tensorflow pandas seaborn matplotlib wandb visualkeras
````

---

## 📊 Training

To train the model:

```python
# Run all cells in the notebook
```

Key components:

* Data generators for augmentation
* Model building (VGG16 + others)
* Training with checkpoints and wandb tracking

---

## 🧪 Evaluation

The model evaluates accuracy and loss on the test dataset. Confusion matrix and other visualizations are included to understand performance.

---

## 🛠️ Dependencies

* TensorFlow / Keras
* pandas, numpy
* seaborn, matplotlib
* wandb
* visualkeras

---

## 📈 Example Results

Example training curves and confusion matrices are available in the notebook.

---

## 🤝 Contributing

Feel free to fork and submit pull requests. Suggestions and feedback are always welcome!

---

## 📜 License

Feel Free to use this project.
---
