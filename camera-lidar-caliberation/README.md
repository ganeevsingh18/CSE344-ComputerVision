# CV_Assignment2

This subdirectory contains my submissions for **Project 2** of the Computer Vision course (CSE344 / CSE544 / ECE344 / ECE544) for the year 2024.  
The assignment covers 3D transformations, camera calibration, and LIDAR-camera cross-calibration.

---

## Q1: `q1_2021389_HW2.py`

**Objective:** Work with 3D transformations and rotations.  
**Contributions:** Derived transformation matrices, computed transformed coordinates, identified combined rotation axis and angle, and validated results using Rodrigues’ formula.  

---

## Q2: `q2_2021389_HW2.py`

**Objective:** Derive the formula for rotating a vector about an arbitrary axis.  
**Contributions:** Proved the rotation expression using cross product and projection terms, explaining the geometric intuition behind it.  

---

## Q3: `q3_2021389_HW2.py`

**Objective:** Relate image points across two cameras under pure rotation.  
**Contributions:** Derived the homography relation `x1 = Hx2` and expressed H in terms of intrinsic matrices and relative rotation.  

---

## Q4: `q4_2021389_HW2.ipynb` – Camera Calibration

**Objective:** Estimate intrinsic, extrinsic, and distortion parameters using chessboard images.  
**Contributions:**  
- Estimated intrinsic and extrinsic parameters.  
- Modeled distortion and undistorted raw images.  
- Computed reprojection error with plots.  
- Visualized detected vs. reprojected corners.  
- Computed plane normals for calibration images.  

---

## Q5: `q5_2021389_HW2.ipynb` – Camera-LIDAR Cross-Calibration

**Objective:** Estimate the transformation between camera and LIDAR frames.  
**Contributions:**  
- Computed plane normals and offsets from LIDAR point clouds.  
- Derived and implemented transformation equations.  
- Projected transformed LIDAR points onto the image plane.  
- Analyzed alignment errors with cosine distance and histograms.  
- Visualized normal vectors for sample pairs.  

---

