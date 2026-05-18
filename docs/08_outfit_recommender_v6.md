# Outfit Recommendation System V6
Hybrid Deep Learning + Manual Feature Engineering

## Overview

Version 6 combines deep-learning image embeddings with handcrafted visual features to improve fashion outfit recommendations.

The system uses MobileNetV2 for deep feature extraction and combines it with manual features such as:

- Dominant colors
- Brightness
- Contrast
- Edge density
- Texture

This hybrid approach improves visual similarity matching by combining semantic understanding with visual aesthetic analysis.

---

## Technologies Used

- Python
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn
- TensorFlow
- MobileNetV2
- Computer Vision

---

## Features

- Deep-learning feature extraction using MobileNetV2
- Manual feature engineering
- Hybrid feature fusion
- Cosine similarity recommendation engine
- Visual outfit recommendation system
- Improved aesthetic and texture understanding

---

## How It Works

### Step 1 — Load Outfit Images
The system loads all outfit images from the dataset.

### Step 2 — Extract Deep Features
MobileNetV2 generates deep image embeddings for each outfit.

### Step 3 — Extract Manual Features
The system extracts:
- Colors
- Brightness
- Contrast
- Texture
- Edge density

### Step 4 — Normalize Features
Deep and manual features are scaled using StandardScaler.

### Step 5 — Combine Features
Both feature groups are merged into a hybrid feature vector.

### Step 6 — Recommend Similar Outfits
Cosine similarity is used to find visually similar outfits.

---

## Improvements Over V5

V5 used only deep-learning embeddings.

V6 improves recommendations by combining:
- semantic understanding from deep learning
- visual aesthetics from handcrafted features

This creates more balanced and visually accurate recommendations.

---

## Future Improvements

- Gender filtering
- Fashion style classification
- User upload system
- Web application interface
- Personalized recommendations
- Larger outfit dataset

---

## Author

Ousama Alelawi
