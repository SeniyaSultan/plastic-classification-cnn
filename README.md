# Plastic Classification using CNNs 🧠📦

This project uses **Convolutional Neural Networks (CNNs)** to classify different types of plastics — a critical challenge in sustainable recycling efforts. The model is trained to recognize visual differences between plastic types using computer vision techniques.

## 🌍 Background

In the circular economy, moving away from the linear **"Take–Make–Dispose"** model is crucial. Proper plastic classification supports effective recycling, reduces environmental degradation, and fights climate change.

## 🧠 Objective

Use deep learning (CNN) to classify images of **four plastic types** to automate plastic sorting for recycling.

## 🛠️ Steps

1. **Load and Pre-process Data**
   - Resize to 256x256
   - Normalize images (divide by 255)
   - Augment (rotation, flipping, etc.)
   - Split into training and validation (3:1 ratio)

2. **Build CNN Model**
   - Use Conv2D, Pooling, Dense, and Dropout layers
   - Optional: use pretrained model like VGG16 or ResNet50

3. **Train Model**
   - 30 epochs
   - Use `steps_per_epoch = len(train_images) // batch_size`

4. **Evaluate**
   - Plot Accuracy/Loss Graph
   - Display Confusion Matrix

## 🧪 Libraries Used

- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

## 📊 Results

- Final accuracy: ~X%
- Confusion matrix showing correct vs. incorrect classifications

## 📁 Directory Structure
## 👩‍💻 Author

Seniya Sultan Jemal

## ✅ Status

✔️ Completed

