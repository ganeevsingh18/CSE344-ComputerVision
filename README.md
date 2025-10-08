# Computer Vision 2024 – Project Portfolio

This repo contains the projects I completed for the **Computer Vision course (CSE344 / CSE544 / ECE344 / ECE544)** in Spring 2024.  
Each project follows a cycle of **building from scratch → improving with advanced methods → analyzing results and limitations**, helping me grow both technically and intuitively as a computer vision engineer.

---

## Project Highlights

### Project 1 – Image Classification & Segmentation  
- **CNN from scratch:** First model trained on the Russian Wildlife dataset (65% accuracy, F1 0.65). Learned limits of small custom architectures.  
- **Pre-trained ResNet18:** Accuracy improved to 83.5% (F1 0.83) but showed overfitting, highlighting risks of high-capacity models on limited data.  
- **Data augmentation:** Boosted accuracy to 90.1% (F1 0.90), solved overfitting, fixed misclassifications (e.g. black vs brown bear).  
- **Segmentation with DeepLabv3+:** Applied Cityscapes-trained model on Indian Driving Dataset — strong on sky/vegetation/buildings but poor on scooters/pedestrians, showing real-world dataset bias.  
Learned how models evolve step by step and why generalization matters as much as raw accuracy.  

---

### Project 2 – Camera Calibration & LIDAR-Camera Cross-Calibration  
- **Transformations:** Derived rotation/translation matrices and validated with Rodrigues’ formula.  
- **Camera calibration:** Estimated intrinsics, extrinsics, distortion coefficients, and reprojection errors using chessboard images.  
- **Cross-calibration:** Solved for 3D transformation between camera and LIDAR, projected LIDAR points into the image, and analyzed alignment errors.  
Gained hands-on understanding of how multi-sensor systems are aligned in robotics and autonomous driving.  

---

### Project 3 – Epipolar Geometry & Panorama Generation  
- **Theory:** Derived epipoles from the Essential matrix, studied rectification.  
- **Panorama pipeline:** Built with SIFT keypoints, BruteForce + FLANN matching, RANSAC homography, warping, and stitching.  
- **Multi-image panorama:** Extended to stitch an entire sequence.  
Learned the geometry behind stereo vision and applied it to create working panorama stitching from scratch.  

---

### Project 4 – Structure-from-Motion & 3D Reconstruction  
- **Feature pipeline:** Keypoint detection, feature matching, essential matrix estimation.  
- **Triangulation + Bundle Adjustment:** Reconstructed 3D structure and optimized camera poses jointly.  
- **Dense reconstruction:** Generated and visualized detailed 3D point clouds.  
Taught me how multiple CV components come together to recover real-world 3D scenes.  

---

## Takeaways
- Built end-to-end systems: classification, segmentation, calibration, panorama stitching, 3D reconstruction.  
- Experienced both **deep learning** (CNNs, ResNet, DeepLabv3+) and **geometry-based CV** (epipolar geometry, SfM).  
- Learned to analyze **results, biases, and limitations**, not just train models.  
  
