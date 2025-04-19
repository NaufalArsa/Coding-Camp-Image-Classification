# 🐱🐶 Cat vs Dog Image Classification using Convolutional Neural Network

This project demonstrates a complete deep learning pipeline to classify images of cats and dogs using both a **sequential CNN model**.

## 🚀 Highlights

- 🔍 Data preprocessing with **ImageDataGenerator**
- 🔁 Comparison between **custom CNN** and **MobileNetV2 Transfer Learning**
- 🧠 Model improvements via:
  - ✅ EarlyStopping
  - ✅ ReduceLROnPlateau
  - ✅ ModelCheckpoint
- 🧪 Evaluation on a **test set** for fair comparison
- 📈 Training performance visualization
- 💾 Export to **TensorFlow SavedModel**, **TensorFlow Lite**, and **TensorFlow.js**

---

## 🧠 Technologies Used

- TensorFlow & Keras
- ImageDataGenerator
- Matplotlib (for visualization)
- TensorFlow Lite
- TensorFlow.js

---

## 📦 Model Export

After training, the best model is exported into three formats:

- `best_model/` – TensorFlow SavedModel
- `model.tflite` – TensorFlow Lite
- `tfjs_model/` – TensorFlow.js

You can now deploy the model on web, mobile, or edge devices!

---
