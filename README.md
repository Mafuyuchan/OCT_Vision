# OCT Vision: Retinal Disease Detection Using Deep Learning

## Abstract

Early diagnosis of retinal diseases such as Age-related Macular Degeneration (AMD), 
Diabetic Macular Edema (DME), and Retinal Vein Occlusion (RVO) is critical for preserving vision. 
This project implements a deep learning-based classification system using Optical Coherence 
Tomography (OCT) images from the OCTDL dataset. We trained CNN and DenseNet models using TensorFlow, 
demonstrating strong performance in distinguishing retinal conditions. 

The system is integrated into a Streamlit-based user interface, allowing **real-time predictions** 
with confidence scores. This project highlights the potential of AI in **enhancing diagnostic accuracy** 
and supporting ophthalmologists in managing retinal diseases.

## Features
- Data preprocessing and augmentation for OCT images
- CNN model implementation for image classification
- Performance evaluation with accuracy, loss, and metrics visualization
- Modular code for easy extension and experimentation

## Installation
- Python 3.8+
- TensorFlow / PyTorch
- OpenCV, NumPy, Matplotlib

## Usage
1. Clone the repository
2. Prepare OCT dataset
3. Run preprocessing scripts
4. Train the CNN model
5. Evaluate performance

## Contributions
This project was developed collaboratively in 2024. My specific contributions include:
- Implemented the CNN model architecture and training pipeline
- Designed data preprocessing and augmentation scripts
- Developed evaluation scripts for accuracy and performance metrics
- Documented the project workflow and created visualizations for results

## Future Work
- Extend to multimodal imaging data
- Optimize model for deployment on edge devices (TinyML)
- Integrate with real-time clinical analysis pipelines
