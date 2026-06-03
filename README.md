# 🥔 Potato Leaf Disease Detection using Segmentation-Based Deep Learning

## 📌 Overview

This repository contains the complete implementation of a **segmentation-based deep learning framework for potato leaf disease detection**. The research focuses on improving disease classification performance by integrating **transformer-based image segmentation** with powerful **CNN classification models**.

The study demonstrates that accurate segmentation of diseased regions significantly improves classification accuracy, interpretability, robustness, and model stability.

---

## 🎯 Research Objective

The primary objective of this research is to enhance **potato leaf disease classification** by first segmenting diseased regions using a transformer-based segmentation model and then applying deep learning classifiers for disease recognition.

Traditional classification models often process entire leaf images, including irrelevant background information. This research investigates whether **disease-focused segmentation** can improve classification performance.

---

## 🧠 Methodology

The proposed framework consists of two major stages:

### 1️⃣ Disease Region Segmentation

A **SegFormer B2 transformer model** is used to segment infected regions from potato leaf images.

Segmentation helps:

* Remove irrelevant background noise
* Focus the classifier on diseased regions
* Improve model interpretability
* Increase classification robustness and stability

### 2️⃣ Disease Classification

After segmentation, multiple CNN-based classification models are trained and evaluated:

* **EfficientNetB0**
* **ResNet50**
* **MobileNetV3Large**
* **EfficientNetV2B0**

The performance of segmented image inputs is compared against unsegmented baseline images.

---

## 📊 Experimental Findings

Experimental results show that **segmented images consistently outperform unsegmented images** across all classification models.

### Key Observations

✅ Segmentation significantly improves classification accuracy.
✅ Transformer-based segmentation enhances robustness and interpretability.
✅ SegFormer B2 provides highly effective disease region extraction.
✅ Segmented inputs outperform traditional full-image classification.

### Best Result

Among all tested models, **EfficientNetB0 achieved the highest performance**, where:

* **Without Segmentation:** `98.27% Validation Accuracy`
* **With Segmentation:** `99.26% Validation Accuracy`

This demonstrates a substantial performance improvement through segmentation.

---

## 🏆 Model Performance

| Model            | Baseline Accuracy | Accuracy After Segmentation |
| ---------------- | ----------------- | --------------------------- |
| EfficientNetB0   | 98.27%            | **99.26%**                  |
| ResNet50         | Improved          | Improved                    |
| MobileNetV3Large | Improved          | Improved                    |
| EfficientNetV2B0 | Improved          | Improved                    |

---

## 📂 Repository Contents

This repository includes:

* Full preprocessing pipeline
* Dataset preparation scripts
* SegFormer B2 segmentation implementation
* CNN classification model training
* Model evaluation pipeline
* Confusion matrices
* Classification reports
* Training and validation plots
* Accuracy and loss visualization
* Experimental notebooks and scripts

---

## 🛠️ Technologies Used

* **Python**
* **TensorFlow / Keras**
* **PyTorch**
* **SegFormer B2**
* **EfficientNetB0**
* **ResNet50**
* **MobileNetV3Large**
* **EfficientNetV2B0**
* **OpenCV**
* **NumPy**
* **Matplotlib**
* **Scikit-learn**

---

## 📈 Conclusion

This research demonstrates that combining **transformer-based segmentation** with **deep CNN classifiers** provides a highly effective framework for potato leaf disease detection.

The results clearly indicate that segmentation acts as a crucial preprocessing step, significantly improving classification performance. The proposed framework achieves high accuracy and offers better interpretability, making it suitable for precision agriculture and automated plant disease diagnosis.

---

## 🚀 Future Work

Potential future improvements include:

* Real-time disease detection systems
* Mobile or edge-device deployment
* Multi-disease and multi-crop support
* Lightweight architectures for faster inference
* Explainable AI (XAI) integration

---

## 📜 Citation

If you use this work in your research, please cite the corresponding paper.

---

## 👨‍💻 Author

**Sarthak Tiwari**
Researcher | Deep Learning | Computer Vision


