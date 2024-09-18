# Crowd-Counting-from-Drone-Footage-Using-CSRNet-by-Sanket-Shah

This project focuses on estimating the number of people on a bridge from drone footage using computer vision techniques. The main goals of the project include frame sampling, crowd counting, and performance validation.

## Overview

- **Model Used:** CSRNet (Convolutional Neural Network)
- **Video Source:** Drone footage of a bridge https://www.youtube.com/watch?v=y2zyucfCyjM
- **Problem:** Estimating the number of people on the bridge within a specific time window (0:14 to 0:32).
- **Challenges:** Small object sizes in the footage and duplicate frame removal.

## Key Features

- **Frame Sampling & Duplicate Removal:** Extracts frames from the video, removes duplicates, and focuses on a specific time interval.
- **Crowd Counting with CSRNet:** Applies CSRNet to predict the number of people in each sampled frame.
- **Performance Metrics:** Calculates the total crowd count by analyzing sequential frame predictions and taking the maximum count across consecutive frames.
- **Validation Techniques:**
  - Manual counting of selected frames.
  - Mean Absolute Error (MAE) and Mean Squared Error (MSE) for validation.
  - Cross-model comparison with YOLO-based models.
  - Density map visualization for visual validation.

## Conclusion

The project offers an automated solution for crowd counting in challenging scenarios, such as drone footage with small-scale objects. It combines CSRNet’s density map approach with practical validation techniques for reliable predictions.


**Note:** The project will run best in Google Colab

