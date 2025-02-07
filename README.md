# Depth Estimation and Visualization in Google Colab

This project demonstrates real-time depth estimation from webcam images using the DepthAnything model (based on DPT/DINOv2) and custom preprocessing pipelines in Google Colab. The code captures an image from your webcam, applies necessary transforms, predicts a depth map, and then displays the raw image alongside a color-mapped depth image with captions.

## Features

- **Webcam Capture:** Uses JavaScript to capture images directly in Colab.
- **Depth Prediction:** Leverages a pretrained DepthAnything model from the Hugging Face Hub.
- **Custom Preprocessing:** Applies resizing, normalization, and preparation steps.
- **Visualization:** Combines the raw image and the predicted depth map side-by-side with captions.

