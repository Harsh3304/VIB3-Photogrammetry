# VIB3-Photogrammetry 📸
## 📝 Overview
VIB3-Photogrammetry is an advanced photogrammetry solution designed to transform 2D images into precise 3D models. Leveraging cutting-edge computer vision and machine learning techniques, this project enables users to create detailed 3D reconstructions from multiple photographic perspectives.

## ✨ Features
- 🖼️ Convert 2D image sets into high-resolution 3D models
- 🤖 Advanced feature matching and point cloud generation
- 🧩 Multiple reconstruction algorithms
- 📊 Comprehensive image alignment and calibration
- 🔬 Support for various object scales and complexities
- 💻 Cross-platform compatibility
- 🚀 Optimized performance with GPU acceleration

## 🖼️ Screenshots
1. **User Interface**  
   <img src="/Dependencies/UI_SS.png" alt="Input Image Collection" width="700">  

2. **Interactive Layout and Result Screen**  
   <img src="/Dependencies/layout_SS.png" alt="Feature Matching" width="700">  

3. **Wireframe Mesh**  
   <img src="/Dependencies/wireframe_output.jpg" alt="3D Point Cloud" width="700">  


## 📦 Prerequisites
Ensure you have the following dependencies installed:

```bash
pip install opencv-python numpy scipy scikit-image open3d transformations matplotlib plotly
```

## 🚀 Installation
1. Clone the repository:
```bash
git clone https://github.com/Harsh3304/VIB3-Photogrammetry.git
```

2. Install required dependencies:
```bash
pip install -r requirements.txt
```

## 💻 Usage
Basic usage example:
```bash
python photogrammetry.py --input_folder ./images --output_folder ./reconstructions
```

## 🖼️ Project Workflow
1. **Image Capture**
   - Capture multiple overlapping images of the target object
   - Ensure consistent lighting and minimal camera movement

2. **Image Processing**
   - Automatic feature detection
   - Image matching and alignment
   - Point cloud generation

3. **3D Reconstruction**
   - Dense point cloud creation
   - Mesh generation
   - Texture mapping

## 💻 Project Structure
```
VIB3-Photogrammetry/
├── src/
│   ├── feature_matching.py
│   ├── reconstruction.py
│   └── visualization.py
├── examples/
│   └── sample_images/
├── requirements.txt
└── photogrammetry.py
```

## 🛠️ Key Technologies
- OpenCV: Image processing and computer vision
- NumPy: Numerical computing
- SciPy: Scientific computing
- Open3D: 3D data processing
- Matplotlib/Plotly: Visualization

## 🤝 Contributing
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AdvancedReconstruction`)
3. Commit changes (`git commit -m 'Add advanced reconstruction algorithm'`)
4. Push to branch (`git push origin feature/AdvancedReconstruction`)
5. Open a Pull Request

## 📋 Planned Improvements
- [ ] Enhanced GPU acceleration
- [ ] More reconstruction algorithms
- [ ] Improved texture mapping
- [ ] Web interface for reconstruction

## 📞 Contact
Project Maintainer: Harsh3304

E-mail: harshp3304@gmail.com

Project Link: [https://github.com/Harsh3304/VIB3-Photogrammetry](https://github.com/Harsh3304/VIB3-Photogrammetry)

