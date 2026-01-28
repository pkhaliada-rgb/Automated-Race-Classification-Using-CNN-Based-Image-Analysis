# Automated-Race-Classification-Using-CNN-Based-Image-Analysis
A Traffic Sign Detection Model developed using deep learning based computer vision techniques.

**Datasets **
https://www.kaggle.com/datasets/pkdarabi/cardetection/data/code

## Executive Summary

This repository contains a **Traffic Sign Detection System** developed using deep learning techniques.  
The trained model achieves **92.74% mAP@0.50** and demonstrates reliable real-time performance on images and videos.

The system includes an interactive **testing toolkit** that supports single-image, multiple-image, video, webcam, and batch folder inference, making it suitable for research, prototyping, and intelligent transportation applications.

---

## Key Highlights

- ✓ Trained traffic sign detection model (**92.74% mAP@0.50**)
- ✓ Supports image, video, webcam, and batch inference
- ✓ Real-time inference (~18.8 ms per frame)
- ✓ Automatic saving of annotated outputs
- ✓ Clean and reproducible testing workflow

---

## Model Performance

| Metric | Value |
|------|------|
| **mAP@0.50** | **92.74%** |
| **Input Resolution** | 640 × 640 |
| **Average Inference Time** | ~18.8 ms |
| **Status** | Trained & Tested |

---
<img width="3000" height="2250" alt="confusion_matrix" src="https://github.com/user-attachments/assets/450f1269-92b9-4505-ad23-1726832131db" />

<img width="2400" height="1200" alt="training_curves" src="https://github.com/user-attachments/assets/59381d62-412a-4d75-8208-4de2520dca23" />

## Supported Testing Modes

The testing toolkit provides the following options:

1. Single Image Test  
2. Multiple Images Test  
3. Video Test  
4. Webcam Test (if available)  
5. Batch Processing from Folder  

Each mode performs inference and automatically saves annotated results.

---

## Inference Results Summary

### 🖼️ Single Image Testing
- Accurate detection of traffic signs in individual images
- Annotated image saved automatically
- Output directory:
```
runs/detect/image_test/
```

---

### 🖼️🖼️ Multiple Image Testing
- Batch inference on multiple images
- Consistent detection performance
- Output directory:
```
runs/detect/multi_image_test/
```

---

### 🎬 Video Testing (Example Run)

- **Frames processed:** 508  
- **Total detections:** 614  
- **Average detections per frame:** 1.2  
- **Inference time:** ~18.8 ms per frame  
- **Output directory:**
```
runs/detect/video_test/
```

---

## Output Structure

All inference outputs are automatically saved under:

```
runs/
└── detect/
    ├── image_test/
    ├── multi_image_test/
    ├── video_test/
```

---

## Execution Status

- Model loaded successfully  
- All testing modes executed without errors  
- Results generated and stored correctly  

---

## Notes

- Frames with no detections are expected due to scene complexity or visibility conditions.
- When using Google Colab, re-run the upload cell if the file upload widget does not appear.

---

## Project Status

**Current Phase:** Model Trained & Tested  
**Readiness Level:** Research • Prototype • Portfolio-Ready  

---

## Author

**M. Ahmad**  
Machine Learning & Computer Vision Researcher  

---

*This repository demonstrates applied deep learning for traffic sign detection and intelligent transportation systems.*
