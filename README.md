# BIM-vSLAM
**BIM-vSLAM: Bridging BIM and Visual SLAM with Plane-Based Representation for Automated Registration and Image-based Reconstruction**

This repository contains the official implementation of **BIM-vSLAM**, a lightweight monocular visual SLAM system that integrates Building Information Models (BIM) with camera-based localization using plane-based representations.

## 🚀 Code Status
The code will be released after the paper is accepted.
We are currently organizing the implementation to ensure clarity, reproducibility, and ease of use. Please stay tuned for updates.

## ⚙️ Environment Requirements
The proposed framework is implemented in C++ for the core SLAM pipeline, with Python bindings for the segmentation network. All experiments are conducted on the following configuration:

### Hardware
CPU: Intel Core i7-12700
GPU: NVIDIA RTX 3070
OS: Ubuntu 20.04

### Software Dependencies
ROS Noetic – for sensor data handling and inter-process communication
OpenCV – image processing
Eigen – linear algebra operations
g2o – graph optimization
PyTorch – neural network inference (segmentation)
IfcOpenShell – BIM data parsing
A detailed installation guide and Dockerfile will be provided upon code release.

## 📬 Contact
For questions or collaborations, please contact the corresponding authors:
Xiao Zhang: xzhangfk@connect.ust.hk
Changhao Song: csongae@connect.ust.hk

## 📄 Paper
The paper is currently under review for **ISPRS Journal of Photogrammetry and Remote Sensing**.  
If you find this work useful for your research, please cite:

```bibtex
@article{zhang2025bimvSLAM,
  title     = {BIM-vSLAM: Bridging BIM and Visual SLAM with Plane-Based Representation for Automated Registration and Image-based Reconstruction},
  author    = {Zhang, Xiao and Song, Changhao and Liang, Zhenyu and Niu, Zhuoyue and Zhang, Jiaying and Cheng, Jack C.P.},
  journal   = {ISPRS Journal of Photogrammetry and Remote Sensing},
  year      = {2025},
  note      = {Under review}
}
