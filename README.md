🌍 Landslide Detection System (Deep Learning)
📌 Overview

This project uses Deep Learning to detect landslide-prone areas from satellite images.
We implemented and compared models like UNet, UNet++, SegNet, and Vi-UNet (Vision Transformer + UNet) for semantic segmentation.

🚀 Features

Detects landslides from satellite imagery.

Multiple models tested for performance.

Best accuracy achieved with Vi-UNet (95.6%).

Dataset: Kaggle Landslide Satellite Images.

📊 Model Performance
Model	Accuracy (%)
UNet	90.45
UNet++	91.80
SegNet	93.25
Vi-UNet	95.62
🛠️ How It Works

Preprocess satellite images (resize, normalize, augment).

Train deep learning models using TensorFlow/Keras.

Generate masks highlighting landslide areas.

Evaluate using accuracy, precision, recall, and F1-score.

▶️ Usage

Clone the repo and install dependencies:

git clone https://github.com/likith4sai/Landslide-Detection-System-DeepLearning.git
cd Landslide-Detection-System-DeepLearning


🔮 Future Scope

Real-time detection with satellite feeds.

Mobile/edge deployment for field use.

Integration with Digital Elevation Models (DEM).

🧑‍💻 Author

Likith Sai – VIT-AP University
