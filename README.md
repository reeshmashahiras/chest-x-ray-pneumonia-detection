   # Intel-oneAPI-Powered FOR PNEUMONIA DETECTION using Chest X-Ray :
This project harnesses the power of Deep Learning and Intel oneAPI to accurately diagnose pneumonia from X-ray images. By automating the detection process, we aim to expedite diagnosis, enabling timely medical intervention and improving patient outcomes. This solution can be seamlessly integrated into clinical workflows, enhancing efficiency and aiding healthcare professionals in making informed decisions. Whether in hospitals or remote areas, our model provides a reliable tool for pneumonia detection, ensuring widespread accessibility to quality healthcare.
   
# PROBLEM STATEMENT

Diagnosing pneumonia from X-ray images can be slow and error-prone, risking treatment delays and poor patient outcomes. Manual interpretation by healthcare professionals varies in accuracy and can't keep pace with rising pneumonia cases. Our project aims to tackle these issues by creating an automated system using deep learning. By swiftly and accurately detecting pneumonia from X-rays, we aim to enhance patient care and outcomes in healthcare settings.

# SOLUTION

Our solution utilizes **Deep Learning techniques** to tackle the challenge of pneumonia detection in X-ray images. Leveraging the  **TensorFlow and Keras frameworks** , we utilize transfer learning with the VGG16 architecture for feature extraction. Additionally, we incorporate Intel's optimized libraries, such as **scikit-learn-intelex** for accelerated computations and **oneDNN for deep learning optimizations**, ensuring efficient execution on **Intel DevCloud**. Our model is trained on a large dataset, augmented using ImageDataGenerator for robustness. With a focus on accuracy and efficiency, our approach enables swift and reliable diagnosis of pneumonia, contributing to improved healthcare outcomes.

# HOW IT WORKS

"Our pneumonia detection system utilizes deep learning algorithms to analyze X-ray images and determine whether a patient has pneumonia.

**Preprocessing:** X-ray images are preprocessed to enhance clarity and remove noise, ensuring accurate analysis.

**Feature Extraction:** The system extracts meaningful features from the preprocessed images using a pre-trained convolutional neural network (CNN), such as VGG16.

**Model Training:** The extracted features are fed into a fully connected neural network, which is trained on a dataset of labeled X-ray images. During training, the model learns to distinguish between normal and pneumonia-affected images.

**Prediction:** Once trained, the model can predict whether a new X-ray image shows signs of pneumonia. The image is processed through the trained model, which outputs the likelihood of pneumonia presence.

**Classification:** Based on the model's prediction, the system classifies the X-ray image as either normal or pneumonia-affected.

![Screenshot 2024-04-14 202805](https://github.com/reeshmashahiras/chest-x-ray-pneumonia-detection/assets/100523261/6a47c8ab-5548-4434-90b7-0dab33a92c1c)


# TECHNOLOGY STACK :

  1.TensorFlow and Keras for deep learning
  2.scikit-learn-intelex and Intel oneDNN for optimized performance
  3.Jupyter Notebook for interactive development
  4.Python for coding
  5.Intel DevCloud for scalable computation
  6.Kaggle and opendatasets for data access
  7.Matplotlib for data visualization

# INTEL INTEGRATIONS :

 1.Intel Developer Cloud
 2.Intel Distribution or python
 3. Intel scikit-learn
 4.Intel OneDNN ( MKL-DNN)
 5.TensorFlow with Intel optimizations
 6.NumPy and SciPy with Intel optimizations
 
![Screenshot 2024-04-14 212339](https://github.com/reeshmashahiras/chest-x-ray-pneumonia-detection/assets/100523261/13e14e63-ad84-4aac-92a3-6ff103aff7c7)


# ADVANTAGES OF MIGRATING TO ONEAPI:
1. Availability of high computing services.
2. Good developer support.

![Screenshot 2024-04-14 210258](https://github.com/reeshmashahiras/chest-x-ray-pneumonia-detection/assets/100523261/ecea6812-6beb-44cd-871e-23b494efab45)


