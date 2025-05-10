---

# Cats vs Dogs Image Classification using Keras 🐱🐶

This project demonstrates how to build a **Convolutional Neural Network (CNN)** using **Keras** to classify images of **cats** and **dogs**. It uses the popular **Dogs vs Cats dataset** from Kaggle and trains a binary image classifier from scratch.

---

| File                                                                                                                                                           | Description                                                                                                                       |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------- |
| [`cats_vs_dog_classification.ipynb`](https://github.com/HaseebUlHassan437/classification-cats-vs-dogs-using-kesras/blob/main/cats_vs_dog_classification.ipynb) | The main notebook for loading data, preprocessing images, building a CNN, training, and evaluating model accuracy on test images. |


---

## 📦 Dataset

**Kaggle Dogs vs Cats Dataset**
📎 [Click here to access the dataset](https://www.kaggle.com/datasets/salader/dogs-vs-cats)

* Consists of **25,000 labeled images** (12,500 cats & 12,500 dogs).
* Balanced dataset for binary classification.

---

## 🧠 Model Overview

* **Framework**: TensorFlow + Keras
* **Architecture**: Custom-built CNN with:

  * Convolutional layers
  * MaxPooling layers
  * Dropout for regularization
  * Dense layers for final classification
* **Loss Function**: Binary Crossentropy
* **Optimizer**: Adam
* **Metrics**: Accuracy

---

## 🛠️ Requirements

* Python 3.x
* Libraries:

  * `tensorflow`
  * `keras`
  * `matplotlib`

Install with:

```bash
pip install tensorflow keras matplotlib 
```

---

## 🚀 How to Run

1. **Clone the repository**:

```bash
git clone https://github.com/HaseebUlHassan437/classification-cats-vs-dogs-using-kesras.git
cd classification-cats-vs-dogs-using-kesras
```

2. **Download the dataset** from [Kaggle](https://www.kaggle.com/datasets/salader/dogs-vs-cats) and extract it into your working directory.

3. **Open the notebook** in Jupyter or Google Colab and follow the step-by-step code to train and test the model.

---

## 📈 Results

* Achieved high validation accuracy using basic CNN architecture.
* Visualized predictions and loss/accuracy graphs for evaluation.

---

## 📚 Learning Objectives

* Understand the full workflow of image classification with CNNs.
* Learn how to preprocess and augment image datasets.
* Gain hands-on experience with Keras for binary classification.

---

## 👨‍💻 Author

**Haseeb Ul Hassan**
GitHub: [@HaseebUlHassan437](https://github.com/HaseebUlHassan437)

---

## 📜 License

Licensed under the **MIT License** — feel free to use and adapt this project.

---

Let me know if you want a **Colab badge**, or I can also add **model performance graphs** to the README.
