# Outfit Recommendation System V5

## Overview

Version 5 upgrades the recommendation system from handcrafted visual features to deep-learning image embeddings using MobileNetV2.

Instead of comparing only colors and brightness, the system now extracts deep visual features from outfit images using a pretrained convolutional neural network (CNN).

The recommender compares outfit embeddings using cosine similarity to find visually similar fashion styles.

---

## Technologies Used

* Python
* NumPy
* Matplotlib
* Pillow (PIL)
* Scikit-learn
* TensorFlow
* MobileNetV2

---

## New Features in V5

* Deep-learning feature extraction
* Pretrained MobileNetV2 integration
* 1280-dimensional image embeddings
* Cosine similarity recommendation engine
* Improved outfit understanding
* Better visual similarity matching
* Larger outfit dataset

---

## How It Works

### Step 1 — Load Dataset

The system loads all outfit images from the dataset folder.

### Step 2 — Extract Deep Features

Each image is processed through MobileNetV2 to generate a 1280-dimensional feature vector.

### Step 3 — Compare Similarities

Cosine similarity is used to compare feature vectors between outfits.

### Step 4 — Recommend Similar Outfits

The system returns the top visually similar outfits based on deep feature similarity.

---

## Example Workflow

Input outfit image:

* White t-shirt outfit
* Casual beige pants
* Minimal streetwear style

Recommended results:

* Similar streetwear outfits
* Similar silhouettes
* Similar fashion aesthetics
* Similar clothing structure

---

## Project Structure

```text
images/
notebooks/
docs/
```

---

## Future Improvements

* Gender filtering
* Style classification
* Web application interface
* Hybrid recommendation scoring
* User upload system
* Fashion tagging system

---

## Result

V5 represents the transition from traditional feature engineering to deep-learning-based fashion recommendation systems.


# Author

Ousama Alelawi


