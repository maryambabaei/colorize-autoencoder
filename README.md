

## 🎨 Image Colorization with Autoencoder

This project demonstrates the use of an **autoencoder neural network** to colorize grayscale landscape images, restoring their original color with impressive accuracy.

### 📁 Dataset

The dataset includes:
- **7,129** image pairs (grayscale and corresponding color)
- Diverse content: streets, buildings, mountains, glaciers, trees, and other natural & man-made features
- Organized in two folders:
  - `grayscale/` – input images
  - `color/` – target images

### 🧠 Model Overview

- **Autoencoder architecture**
  - Encoder processes grayscale input
  - Decoder reconstructs the color version
- Trained using paired grayscale and color images
- Loss function: Mean Squared Error (MSE)
