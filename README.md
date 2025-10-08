# Computer Vision 2024

This repo contains the projects I completed for the **Computer Vision course (CSE344 / CSE544 / ECE344 / ECE544)** in Winter 2024.  
Each project follows a cycle of **building from scratch → improving with advanced methods → analyzing results and limitations**

## Project Highlights

### Image Classification & Segmentation  
- **CNN from scratch:** First model trained on the Russian Wildlife dataset (65% accuracy, F1 0.65). Learned limits of small custom architectures.  
- **Pre-trained ResNet18:** Accuracy improved to 83.5% (F1 0.83) but showed overfitting, highlighting risks of high-capacity models on limited data.
- **Data augmentation:** Boosted accuracy to 90.1% (F1 0.90), solved overfitting, fixed misclassifications (e.g. black vs brown bear).  
- **Segmentation with DeepLabv3+:** Applied Cityscapes-trained model on Indian Driving Dataset, the model showed strong results on sky/vegetation/buildings but poor on scooters/pedestrians, showing real-world dataset bias. The SOTA model DeepLabv3+ was trained on Cityscape dataset, it failed to generalise against dataset collected on Indian streets.
Learned how models evolve step by step and why generalization matters as much as raw accuracy.  

---

### Camera Calibration & LIDAR-Camera Cross-Calibration  
- **Transformations:** Derived rotation/translation matrices and validated with Rodrigues’ formula.  
- **Camera calibration:** Estimated intrinsics, extrinsics, distortion coefficients, and reprojection errors using chessboard images.  
- **Cross-calibration:** Solved for 3D transformation between camera and LIDAR, projected LIDAR points into the image, and analyzed alignment errors.  
Gained hands-on understanding of how multi-sensor systems are aligned in robotics and autonomous driving.  

---

### Epipolar Geometry & Panorama Generation  
- **Theory:** Derived epipoles from the Essential matrix, studied rectification.  
- **Panorama pipeline:** Built with SIFT keypoints, BruteForce + FLANN matching, RANSAC homography, warping, and stitching.  
- **Multi-image panorama:** Extended to stitch an entire sequence.  
Learned the geometry behind stereo vision and applied it to create working panorama stitching from scratch.  

---

### Vision-Language Models (Segmentation & VQA)  

- **Open-Vocabulary Segmentation (CLIPSeg):**  
  Segmented images using text prompts instead of fixed labels. Applied to the Indian Driving Dataset — learned how prompts like *“road”*, *“person”*, or *“traffic sign”* produce masks directly from language. Compared outputs with ground truth and DeepLabv3+ from Project 1, computing mAP to evaluate strengths and gaps.  

- **Visual Question Answering (BLIP):**  
  Used BLIP to answer natural language questions about images (*“Where is the dog?”*, *“What is the man doing?”*). Extended to a dataset of images + annotated Q&A, computed accuracy, and analyzed failure cases when the model misunderstood context.  
---

## Takeaways
- Built end-to-end systems: classification, segmentation, calibration, panorama stitching, 3D reconstruction.  
- Experienced both **deep learning** (CNNs, ResNet, DeepLabv3+) and **geometry-based CV** (epipolar geometry, SfM).  
- Learned to analyze **results, biases, and limitations**, not just train models.  
  