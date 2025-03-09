# Image Classification Using SDH and GLCM

## Overview
This project focuses on classifying hyper-spectral remotely sensed images using texture-based feature extraction methods. The classification models leverage **Sum-Difference Histogram (SDH)** and **Grey-Level Co-occurrence Matrices (GLCM)** to enhance feature representation and improve model accuracy.

## Project Details
- **Domain**: Machine Learning, Image Classification
- **Duration**: March 2023 - May 2024
- **Guide**: Prof. B. K. Mohan
- **Tech Stack**: Python, NumPy, OpenCV, Scikit-learn

## Dataset
The **Imagerar dataset** is used for training and testing, containing **10,000+ images** with hyper-spectral properties. The dataset provides a rich set of spectral bands and textures, making it suitable for advanced classification techniques.

## Key Tasks & Methodology
- **Feature Extraction**:
  - Implemented **SDH** (Sum-Difference Histogram) for texture-based feature representation.
  - Utilized **GLCM** (Grey-Level Co-occurrence Matrix) to extract spatial texture features.
- **Model Deployment**:
  - Trained a **Random Forest Classifier** to classify image textures.
  - Achieved an accuracy of **58%** on the test dataset.

## Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/Devil00727/Image-Classification-Using-SDH-and-GLCM.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook FInal_Sourve_Code.ipynb
   ```

## Usage
- The Jupyter Notebook contains end-to-end implementation, including feature extraction and model training.
- Modify feature extraction parameters or experiment with different classifiers to enhance performance.

## Results
- The **Random Forest classifier** achieved **58% accuracy** on the Imagerar dataset.
- Performance metrics and visualizations are provided in the notebook.

## Contributors
- **Vishal Gautam** (IIT Bombay)
- Guide: **Prof. B. K. Mohan**

## License
This project is open-source and available under the **MIT License**.

---
For more details, refer to `FInal_Sourve_Code.ipynb`.

