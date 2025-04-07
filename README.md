# Indian Sign Language Detection using YOLOv11

This project implements Indian Sign Language (ISL) gesture detection using a custom dataset and trained YOLOv11 models. It aims to recognize hand gestures for communication with people who are deaf and mute. With the help of a project like this, a noraml person who don't known sign language can communicate with the ones with the disabilities who know only sign language to communicate. This helps to reduce the communication gape between the people.

## 📁 Contents

- `https://github.com/Ali498609/Indian-Sign-Language-detection/releases/tag/v1.0/`:  
  Contains the ISL dataset and trained YOLOv11 model weights:
  - `best.pt` (best performing checkpoint)
  - `last.pt` (final checkpoint after training)
  
- `isl_detection.ipynb`:  
  Jupyter Notebook for running inference and testing the model.

## 🚀 Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/Ali498609/Indian-Sign-Language-detection.git
cd Indian-Sign-Language-detection

# 2. Download the dataset and models
# (from the Releases tab or use this direct link)
# https://github.com/Ali498609/Indian-Sign-Language-detection/releases/tag/v1.0

# 3. Unzip the downloaded file
unzip ISL_Detection_w/_dataset.zip

# 4. Run the notebook
# Open 'isl_detection.ipynb' in Jupyter or VS Code and run the cells
```

## ✨ Demo

![ISL Detection Demo](Demo video for Indian sign language detection.mp4)
