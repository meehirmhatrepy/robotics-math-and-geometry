# 🤖 Robotics Math & Geometry  
A clean, beginner-friendly, notebooks-based repository covering the essential mathematical tools.

This repo is designed for hands-on learning with **Jupyter notebooks**, covering everything from camera geometry → SE(3) transforms → linear algebra foundations.

---

## 📂 Repository Structure



robotics-math-and-geometry/
│
├── README.md
│
├── camera_geometry/
│ └── camera_geometry.ipynb
│
├── linear_algebra/
│ └── linear_algebra.ipynb
│
└── se3_transforms/
└── se3_transforms.ipynb


---

# 🧠 Overview of Notebooks

## 📸 1. `camera_geometry/camera_geometry.ipynb`
This notebook explains the fundamentals of the **pinhole camera model** and practical 3D vision operations used in robotics and SLAM.

### **Topics Covered**
- Building camera intrinsics matrix \(K\)
- Projecting 3D points → 2D pixels  
  - \(p = K [X/Z, Y/Z, 1]^T\)
- Backprojecting depth → 3D  
  - \(X = (u - c_x) d / f_x\)
- Image undistortion  
- Interactive widgets for understanding camera geometry  
- All formulas, code, and visual examples included

---

## 🧮 2. `linear_algebra/linear_algebra.ipynb`
A practical introduction to the **linear algebra** used in robotics, including:

### **Topics Covered**
- Vectors, matrices, norms  
- Rotation matrices (Rx, Ry, Rz)  
- Orthonormality & right-handed coordinate frames  
- Determinants and eigen decomposition  
- Solving linear systems  
- Geometric interpretation of matrices  
- Interactive visualizations for understanding rotations and transformations

This notebook is designed as the mathematical foundation for the other modules.

---

## 🔄 3. `se3_transforms/se3_transforms.ipynb`
This notebook covers **robot motion, SE(3), and rigid-body transformations**, the core of modern robotics and SLAM.

### **Topics Covered**
- SO(3): Rotation groups  
- SE(3): Rigid transforms in 3D  
- Homogeneous transformation matrices  
- Combining rotations + translations  
- Camera/world coordinate conversions  
- Inverse transforms  
- Open3D visualizations for poses  
- Interactive widgets for understanding SE(3)

---

# 🎯 Target Audience
This repository is ideal for:

- Robotics beginners  
- SLAM / 3D reconstruction learners  
- Computer vision students  
- Researchers needing clean explanations  
- Anyone building intuition behind geometric operations  

Everything is fully explained—**math + code + intuition**.

---

# 🛠 Requirements
- Python 3.8+
- Jupyter Notebook / JupyterLab  
- NumPy  
- OpenCV (for camera geometry)  
- Matplotlib  
- ipywidgets  
- Open3D (optional, for SE3 visualization)

Install dependencies:

```bash
pip install numpy opencv-python matplotlib ipywidgets open3d


Enable widgets:

jupyter nbextension enable --py widgetsnbextension

🚀 Getting Started

Clone the repo:

git clone https://github.com/meehirmhatrepy/robotics-math-and-geometry.git
cd robotics-math-and-geometry


Open a notebook:

jupyter notebook camera_geometry/camera_geometry.ipynb
