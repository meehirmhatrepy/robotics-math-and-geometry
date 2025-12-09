📚 Robotics Math and Geometry

This repository contains three learning modules covering the essential mathematical tools used in 3D geometry, computer vision, and transformations.
Each module is implemented as a Jupyter Notebook with explanations, formulas, and interactive visualizations.

📁 Folder Structure
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

📘 1. Linear Algebra Notebook

location: linear_algebra/linear_algebra.ipynb

Covers the fundamentals required for 3D geometry and transformations:

✅ Included Topics

Vectors and operations

dot product

cross product

vector norm and normalization

Matrices

matrix multiplication

determinants & geometric meaning

inverse, transpose, orthogonal matrices

Decompositions

QR decomposition (Gram–Schmidt)

Singular Value Decomposition (SVD)

Interactive widgets for

visualizing vector addition

dot product as projection

cross product direction

matrix transformations

🎯 Purpose

You learn the math tools needed before moving into 3D rotations and camera models.

📘 2. SE(3) Transformations Notebook

location: se3_transforms/se3_transforms.ipynb

Explains how 3D rotations and translations are represented and combined.

✅ Included Topics

Rotation matrices

Rx, Ry, Rz

properties (orthogonality, determinant)

Euler angles

conversion ↔ rotation matrices

Quaternions

conversion ↔ rotation matrices

advantages over Euler angles

SE(3)

4×4 transformation matrices

combining rotation + translation

inverse transform

applying transforms to points

homogeneous coordinates

Interactive 3D visualization of

rotated point clouds

transformed coordinate frames

effect of changing roll/pitch/yaw/translation

🎯 Purpose

You learn how to represent orientation and position in space, and how to transform 3D points.

📘 3. Camera Geometry Notebook

location: camera_geometry/camera_geometry.ipynb

Covers the mathematical model of a pinhole camera.

✅ Included Topics

Camera intrinsics

focal length

principal point

pixel scaling

building the intrinsic matrix

Projection

3D → 2D projection

homogeneous coordinates

perspective divide

Backprojection

using depth to recover 3D points

Distortion

radial & tangential distortion

using OpenCV to undistort images

Interactive visualizations

sliders to change focal length

3D point projection demo

depth → point cloud generation

🎯 Purpose

You learn how cameras see the world and how 3D information becomes 2D images.

📦 Requirements

Python 3.8+

NumPy

Matplotlib

OpenCV (for camera geometry)

ipywidgets (for interactivity)

Jupyter Notebook/Lab

✔ How to Use

Clone the repo and open any notebook:

git clone https://github.com/meehirmhatrepy/robotics-math-and-geometry.git
cd robotics-math-and-geometry
jupyter notebook

📌 Goal of This Repository

To build a strong, practical foundation in:

linear algebra for geometry

3D transformations

camera projection models

with simple explanations + code + interactive visualizations.
