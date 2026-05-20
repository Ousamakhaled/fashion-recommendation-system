# Outfit Recommendation System V7

## Overview
V7 improves the recommendation system by combining:

- Deep learning image embeddings (MobileNetV2)
- Manual visual features
- Metadata-based scoring

The goal of this version is to create more context-aware outfit recommendations instead of relying only on visual similarity.

---

## Features Used

### Deep Features
Extracted using MobileNetV2:
- Semantic outfit understanding
- Shape and clothing structure
- General visual similarity

### Manual Features
Custom-engineered visual features:
- Dominant colors
- Brightness
- Contrast
- Edge density
- Texture

### Metadata Features
Additional contextual labels:
- Gender
- Style
- Season
- Occasion

---

## How V7 Works

1. Extract deep learning features from images
2. Extract manual visual features
3. Scale both feature groups
4. Combine them into a hybrid feature vector
5. Compare outfits using cosine similarity
6. Add metadata matching score
7. Rank the final recommendations

---

## Improvements Over V6

V6:
- Hybrid visual similarity only

V7:
- Hybrid visual similarity
- Metadata-aware ranking
- More context-sensitive recommendations

This allows the system to better understand:
- Seasonal compatibility
- Style matching
- Occasion matching
- Gender-based filtering

---

## Technologies Used

- Python
- TensorFlow / Keras
- MobileNetV2
- OpenCV
- NumPy
- Scikit-learn
- PIL
- Matplotlib

---

## Current Limitation

Only a small number of images currently contain metadata labels.
Because of this, recommendation diversity is still limited.

Future improvement:
- Automatic metadata generation
- Larger labeled dataset
- Web application integration

---

## Future Goals

- Automatic fashion tagging
- User image upload system
- Real-time outfit recommendations
- Fashion search engine
- Full-stack deployment
