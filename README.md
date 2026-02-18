# OptiBraille  
### AI-Powered Braille Recognition System using Computer Vision

---

##  Abstract

OptiBraille is a deep learning–based computer vision system designed to recognize and translate Braille patterns into readable digital text. The project aims to bridge the accessibility gap for visually impaired communities by enabling automated interpretation of Braille documents using image processing and neural network architectures.

This system focuses on accurate Braille dot detection, robust feature extraction, and high-performance classification under varying lighting and noise conditions.

---

##  Problem Statement

Despite Braille being a critical literacy medium for visually impaired individuals, digitizing physical Braille documents remains challenging.

Key difficulties include:
- Variations in lighting conditions
- Image noise
- Dot spacing inconsistencies
- Partial occlusions

OptiBraille addresses these challenges using a structured computer vision pipeline combined with deep learning.

---

##  Proposed Solution

The system performs:

1. **Image Acquisition**
2. **Preprocessing**
   - Grayscale conversion
   - Noise reduction
   - Thresholding
3. **Braille Dot Detection**
4. **Feature Extraction**
5. **Neural Network Classification**
6. **Character-to-Text Conversion**

---

##  Model Architecture

<img width="757" height="1353" alt="model_architecture" src="https://github.com/user-attachments/assets/c0eb5796-5b48-4428-b62f-26f7d9d1b05e" />



The classification model leverages a convolutional neural network architecture optimized for:
- Spatial feature extraction
- Pattern generalization
- Robust classification accuracy

---

##  Experimental Results

<img width="1000" height="800" alt="results" src="https://github.com/user-attachments/assets/62fed8bb-4509-4c33-8d02-d72d0b2846b6" />


- High classification accuracy achieved on validation data
- Stable performance under illumination variations
- Low misclassification rate across tested samples

---

##  Sample Predictions

<img width="1200" height="1000" alt="sample_predictions" src="https://github.com/user-attachments/assets/923209ff-dcf2-4eeb-906b-efe85898368d" />


The model successfully converts detected Braille cells into readable alphanumeric output.

---

##  Tech Stack

- Python
- OpenCV
- NumPy
- TensorFlow / PyTorch
- Matplotlib
- Google Colab

---

##  Innovation Highlights

✔ Automated Braille-to-text conversion  
✔ Noise-robust preprocessing pipeline  
✔ Optimized CNN-based classification  
✔ End-to-end recognition pipeline  

---

##  Future Work

- Mobile application deployment  
- Real-time Braille scanning  
- Multi-language Braille support  
- Edge-device optimization  

---

##  Code Availability

The complete training pipeline and implementation are not publicly available.

For academic collaboration or demonstration inquiries, please contact the author.

---

##  Author
*VIJAY M*
Artificial Intelligence & Machine Learning Enthusiast  
Focused on Accessible AI Solutions
