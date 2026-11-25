# 🖼️ Image Data Preprocessing for Computer Vision & CNNs

A hands-on Jupyter Notebook workflow demonstrating essential image data preprocessing, color-space conversion, spatial resizing, pixel normalization, and visual verification techniques using **OpenCV**, **Matplotlib**, and **NumPy**.

---

## 📌 Overview
Raw image datasets vary widely in resolution, channel ordering, and pixel intensity distributions. Before feeding images into Convolutional Neural Networks (CNNs) or deep learning pipelines, consistent preprocessing is critical for stable gradient updates and accurate feature extraction.

This repository walks through core image manipulation and preprocessing operations step-by-step, comparing **OpenCV (`cv2`)** and **Matplotlib (`plt`)** rendering pipelines side by side.

---

## 📂 Repository Contents

```text
Image_Data_Preprocessing/
├── Image_Data_Preprocessing.ipynb   # Main notebook covering loading, resizing, color spaces & normalization
├── cv2_dog.png                      # Sample output rendered/saved via OpenCV (BGR/RGB handling)
├── mpl_dog.png                      # Sample output rendered/saved via Matplotlib
├── archive.zip                      # Compressed sample image dataset (extract to Dataset/ to run locally)
├── .gitignore                       # Excludes extracted Dataset/ directory and Jupyter checkpoints
└── README.md
