# 🩺 Pneumonia Detection with ResNet18

This project uses deep learning with a **pre-trained ResNet18** model to classify chest X-ray images and detect pneumonia. The model is trained using PyTorch on the publicly available Chest X-Ray dataset.

---

## 🧠 Project Overview

Pneumonia is a potentially life-threatening lung infection. This project builds a convolutional neural network model using **transfer learning** to automatically identify pneumonia from chest X-rays.

---

## 📁 Dataset

We use the **Chest X-Ray Images (Pneumonia)** dataset provided by Kaggle:

🔗 [Chest X-Ray Pneumonia Dataset on Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

### Expected Folder Structure

After downloading the dataset, place the files in a folder named `chest_xray` in the same directory as the notebook.

---

## 🧰 Model Details

- **Architecture:** ResNet18 (transfer learning)
- **Framework:** PyTorch
- **Training:** Fine-tuned on chest X-ray data
- **Evaluation Metrics:** Accuracy, Loss, Confusion Matrix

The model will be trained when you run the notebook. **No pre-trained `.pth` file is included** due to GitHub size limitations.

---

## 🔧 Installation & Requirements

Install the required dependencies using:

```bash
pip install -r requirements.txt

## 🚀 Running the Project

1-Download the dataset and place it in a chest_xray/ folder.

2-Open the notebook.

3-Open the project "Pneumonia_Predection.ipynb".

4-Run all the cells to train and evaluate the model.

## The trained model will be automatically saved as:

"pneumonia_detection_model.pth"
