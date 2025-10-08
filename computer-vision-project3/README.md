# CV_Assignment3

This subdirectory contains my submissions for **Project 3** of the Computer Vision course (CSE344 / CSE544 / ECE344 / ECE544) for the year 2024.  
The assignment covers epipolar geometry theory and practical panorama generation.

---

## Q1: `q1_2021389_HW3.py` – Epipolar Geometry

**Objective:** Work with the Essential matrix, epipoles, and stereo constraints.  
**Contributions:**  
- Derived epipoles as null-space and left null-space of the Essential matrix.  
- Constructed the Essential matrix for pure horizontal translation and showed that corresponding points share the same y-coordinate.  
- Derived the rotation matrix for stereo rectification and explained its role in mapping epipoles to infinity.  

---

## Q2: `q2_2021389_HW3.ipynb` – Panorama Generation

**Objective:** Build a complete panorama stitching pipeline using feature detection, matching, and image alignment.  
**Contributions:**  
- **Keypoint Detection:** Extracted SIFT keypoints and descriptors, visualized them on images.  
- **Feature Matching:** Implemented BruteForce and FlannBased matchers, displayed matched pairs.  
- **Homography Estimation:** Used RANSAC to estimate a robust homography matrix.  
- **Perspective Warping:** Warped images with the homography, displayed panorama edges.  
- **Stitching:** Combined two images into a panorama, visualized raw and blended results.  
- **Multi-Stitching:** Extended stitching to multiple images, producing a complete panorama.  

---

