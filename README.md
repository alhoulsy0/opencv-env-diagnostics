# 🛠️ OpenCV Environment Diagnostics

A specialized utility script for Computer Vision developers to quickly audit their local environment. 

## 🌟 Why this exists?
OpenCV performance depends heavily on whether hardware acceleration (OpenCL/CUDA) and CPU optimizations are active. This tool provides a one-second audit of these settings to prevent performance bottlenecks.

## 📊 Features
* **OpenCL Detection:** Checks for GPU/Integrated Graphics acceleration availability.
* **Optimization Audit:** Verifies if `cv2.useOptimized()` is active.
* **System Meta:** Reports Python and OS architecture details.

## 🚀 Usage
```bash
python scripts/check_vision_env.py
