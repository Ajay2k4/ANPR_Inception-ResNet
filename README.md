# ANPR_Inception-ResNet
Automatic Number Plate Recognition (ANPR) System
Overview
Welcome to the Automatic Number Plate Recognition (ANPR) System project! This repository contains our work on developing a robust and efficient ANPR system leveraging the power of computer vision and deep learning. Our system aims to accurately detect and recognize vehicle number plates in real-time, making it a valuable tool for traffic management, law enforcement, and smart city applications.
Automatic Number Plate Recognition (ANPR) System! This project applies Deep Learning & OCR to accurately detect and recognize vehicle number plates in real-time. 🚀



🔹 Project Overview
Our ANPR system follows a structured pipeline:
🔸 Data Preparation – Grayscale conversion, bilateral filtering, edge detection (Canny), and data augmentation (rotation, scaling, flipping) for better generalization.
🔸 Model Training – Used InceptionResNetV2 for deep feature extraction, fine-tuned with custom layers, and applied transfer learning for improved performance.
🔸 License Plate Detection – Deployed the trained model for plate detection, using non-maximum suppression to refine accuracy.
🔸 License Plate Extraction – Cropped detected plates for further processing.
🔸 Optical Character Recognition (OCR) – Used EasyOCR for high-accuracy text extraction across various fonts and languages, with post-processing for standardization.
🔸 Output Generation – Displayed or stored recognized plate numbers for further use.

🎯 Key Learnings from this Project
✅ Improved my Computer Vision & Deep Learning skills.
✅ Worked with InceptionResNetV2 for Object Detection.
✅ Enhanced OCR performance using EasyOCR & preprocessing techniques.
✅ Optimized real-time processing for live video stream recognition.


🚗 Results: Achieved 95%+ accuracy in recognizing alphanumeric characters from number plates, validated by precision, recall, and F1-score metrics!
Looking forward to working on more impactful AI solutions!
Would love to connect with fellow AI & Computer Vision enthusiasts! Let’s discuss more innovative AI-driven solutions. 🚀

<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/13b0459b-1452-4737-9912-527ed6981efd" />

Key Features
Advanced Preprocessing: The system enhances image quality through grayscale conversion, bilateral filtering, and edge detection using the Canny algorithm, ensuring high clarity for contour extraction.
Deep Learning with InceptionResNetV2: Utilizes the InceptionResNetV2 architecture for superior feature extraction and object detection, enhanced through transfer learning techniques.
Optical Character Recognition (OCR): Employs EasyOCR for precise text extraction from detected number plates, providing flexibility across different languages and fonts.
Real-time Performance: Optimized for real-time processing, enabling quick and accurate number plate recognition from live video streams and surveillance footage.
Repository Contents
ANPR CNN_EasyOCR Report.pdf: Detailed documentation of the project, covering the methodology, experimental results, and potential future enhancements.
Image_CSv.ipynb: Jupyter Notebook for image preprocessing tasks, including conversion to CSV format.
Object_Detection.ipynb: Jupyter Notebook for training and evaluating the ANPR model using the InceptionResNetV2 architecture.
Methodology
Image Preprocessing:

Convert input images to grayscale.
Apply bilateral filtering to reduce noise.
Use data augmentation techniques (rotation, scaling, flipping) to improve model generalization.
Model Training:

Leverage the InceptionResNetV2 architecture for robust feature extraction.
Fine-tune with custom dense layers for specific classification and regression tasks.
Implement transfer learning to enhance performance with limited annotated data.
Object Detection:

Deploy the trained model to detect number plates in new images.
Use non-maximum suppression to eliminate duplicate detections and improve accuracy.
Optical Character Recognition (OCR):

Extract characters from the detected number plates using EasyOCR.
Perform post-processing to refine and standardize the extracted text.

Results
Our ANPR system demonstrates high accuracy, achieving over 95% in recognizing and extracting alphanumeric characters from number plates. Performance metrics such as precision, recall, and F1 score further validate its efficacy in diverse conditions.
