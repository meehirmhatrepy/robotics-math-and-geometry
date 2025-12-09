# 🚀 Robotics Math & Geometry

A polished, modern, and professional repository covering the **core mathematical foundations** used in robotics, 3D vision, SLAM, and graphics.

This repo contains **three high‑quality, interactive Jupyter notebooks**, each focused on one pillar of robotics math:

---

## 📁 Repository Structure

```
robotics-math-and-geometry/
│
├── README.md
│
├── linear_algebra/
│   └── linear_algebra.ipynb
│
├── se3_transforms/
│   └── se3_transforms.ipynb
│
└── camera_geometry/
    └── camera_geometry.ipynb
```

---

# 📘 1. Linear Algebra

**Path:** `linear_algebra/linear_algebra.ipynb`

This notebook covers the mathematical fundamentals needed for robotics:

### ✔ Vector Operations  
- Dot product  
- Cross product  
- Norms (L2)  
- Normalization  

### ✔ Matrix Operations  
- Matrix multiplication  
- Determinant  
- Transpose  
- Inverse  

### ✔ Decompositions  
- QR decomposition (Gram–Schmidt)  
- SVD  
- Eigenvalues (intro)  

### ✔ Visualizations  
- 3D vector plots  
- Projection demos  
- Linear transformations in 2D & 3D  

---

# 🔷 2. SE(3) Transformations

**Path:** `se3_transforms/se3_transforms.ipynb`

Covers the full theory and implementation of rigid body transforms.

### ✔ Rotations  
- Rotation matrices Rx, Ry, Rz  
- SO(3) properties  
- Euler angles (ZYX order)  
- Gimbal lock explanation  

### ✔ Quaternions  
- Quaternion definition  
- Rotation matrix ↔ quaternion  
- Normalization, unit quaternions  

### ✔ SE(3)  
- 4×4 transformation matrices  
- Composition of transforms  
- Inverse transforms  
- Homogeneous coordinates  

### ✔ Applications  
- Apply SE(3) to 3D point clouds  
- Visualize transforms with 3D plots  
- ipywidgets sliders for rotations & translations  

---

# 🎯 3. Camera Geometry

**Path:** `camera_geometry/camera_geometry.ipynb`

Covers the mathematical model used in computer vision & robotics.

### ✔ Camera Intrinsics  
- Focal length  
- Principal point  
- Camera matrix K  

### ✔ Projection & Backprojection  
- 3D → 2D projection  
- Depth backprojection  
- Ray casting  

### ✔ Distortion Models  
- Radial distortion  
- Tangential distortion  
- Undistortion using OpenCV  

### ✔ Visualizations  
- Image plane diagrams  
- Pose + projection demos  
- Camera frustums in 3D  

---

# 🌟 Why This Repository Is Valuable

- Demonstrates **real robotics foundations**  
- Shows **clear mathematical understanding**  
- Each notebook has:
  - Explanations  
  - Equations  
  - Code  
  - Visualizations  
  - Interactive widgets  

Perfect for showcasing skills to employers for roles in:

- Robotics Perception  
- Computer Vision  
- SLAM / 3D Reconstruction  
- Autonomous Systems  
- AR/VR Geometry  

