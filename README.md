# 🌍 Landslide Detection System (Deep Learning)

## 📌 Overview
This project uses **Deep Learning** to detect landslide-prone areas from **satellite images**.  
We implemented and compared **UNet, UNet++, SegNet, and Vi-UNet (Vision Transformer + UNet)** for **semantic segmentation**.  

This repository is based on our IEEE research paper *"Landslide Detection for Construction Safety"* (2025), where we explored deep learning models to enhance **construction safety** by identifying unstable terrain using satellite imagery.

---

## 🚀 Features
- Detects landslides from satellite imagery  
- Multiple models tested; **Vi-UNet** performed best (≈95.6% accuracy)  
- Dataset: Kaggle satellite images with masks (details below)  

---

## 📊 Model Performance
| Model   | Accuracy (%) |
|---------|--------------|
| UNet    | 90.45 |
| UNet++  | 91.80 |
| SegNet  | 93.25 |
| Vi-UNet | **95.62** |

---

## 🗂️ Dataset
- **Source:** High-resolution satellite images from **Kaggle**  
- Two categories:  
  - Landslide images with binary masks  
  - Non-landslide/background images  
- **Preprocessing:**  
  - Augmentation: rotation, flipping, scaling, color shifts  
  - Resize to **224×224×3**  
  - Normalize pixel values to **[0, 1]**  

---
## 🧠 How It Works
- Preprocess images  
- Train segmentation models  
- Generate masks highlighting landslide areas  
- Evaluate using accuracy, precision, recall, F1-score, and IoU  

---

## 🔮 Future Scope
- Real-time detection with satellite feeds  
- Mobile/edge deployment for field use  
- Integration with Digital Elevation Models (DEM)  

---

## 🧑‍💻 Authors
- **Likith Sai** – VIT-AP University  


## ▶️ Quickstart
Clone the repository and install dependencies:
```bash
git clone https://github.com/likith4sai/Landslide-Detection-System-DeepLearning.git
cd Landslide-Detection-System-DeepLearning


