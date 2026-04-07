# 🌿 Hybrid Deep Learning Framework for Plumbago Identification

## 📌 Project Overview

This project builds a hybrid deep learning model to classify plant leaf images as **Plumbago** or **Not Plumbago**.
It combines multiple architectures (EfficientNet, ResNet, Vision Transformer) to improve prediction accuracy and robustness.

---

## 🚀 Live Demo

👉 Try the project here:
https://huggingface.co/spaces/surya098/plumbago

---

## 📂 Repository Contents

```
plumbago/
│
├── hybrid-deep-learning-framework-for-plumbago.ipynb
├── README.md
```

> ⚠️ The trained model file is not included in this repository due to GitHub size limits.

---

## 📥 Download Model File (Required)

The trained model is available in the **Releases** section.

### Steps:

1. Go to **Releases** in this repository
2. Download:
   fusion_model_best.pth
3. Place it in the same folder as the notebook

Final structure:

```
plumbago/
│
├── hybrid-deep-learning-framework-for-plumbago.ipynb
├── fusion_model_best.pth
```

---

## ▶️ How to Run the Project

1. Open the notebook (`.ipynb`) using Jupyter or VS Code
2. Run all cells sequentially
3. The model will load automatically
4. Use the Gradio interface to upload a leaf image

---

## 🧠 Model Architecture

* EfficientNet (feature extraction)
* ResNet (deep representation)
* Vision Transformer (global context)
* Fusion layer combining all outputs

---

## 🖥️ Features

* Hybrid deep learning model
* Leaf segmentation preprocessing
* Explainable AI (saliency maps)
* Interactive UI with Gradio

---

## ⚙️ Requirements

Install dependencies:

```
pip install torch torchvision gradio numpy pillow
```

---

## 📊 Output

* Prediction: Plumbago / Not Plumbago
* Confidence score
* Heatmap-based explanation

---

## 💡 Important Notes

* File name must be exactly:
  fusion_model_best.pth
* Keep the model file in the same folder as the notebook
* Do not rename the file

---

## 👨‍💻 Author

Surya

---

## 📌 Conclusion

This project demonstrates how hybrid deep learning and explainable AI can be used for accurate and interpretable plant identification.
