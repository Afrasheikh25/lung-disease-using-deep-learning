 Lung Disease Classification Using Deep Learning 🩺🧠
 
       This project classifies chest X-ray images into four categories: **COVID-19**, **Pneumonia**, **Tuberculosis**, and **Normal** using a **fine-tuned VGG19 model** with transfer learning.

📌 Overview:

Lung diseases like pneumonia, tuberculosis, and COVID-19 are among the leading causes of death globally. Timely and accurate diagnosis via CXR images can be life-saving — yet manual analysis is time-consuming and error-prone.
Our solution uses **Deep Learning (CNN + Transfer Learning)** to automate and enhance CXR image classification with **96% accuracy**, improving efficiency and clinical reliability.

 🧰 Tech Stack:

- Python 3.6+
- TensorFlow 2.x, Keras
- OpenCV, NumPy, Pandas
- Matplotlib, Seaborn, scikit-learn
- Streamlit (for deployment)

🚀 Key Features:

- Fine-tuned **VGG19** model for feature extraction  
- **Global Average Pooling**, **Dense**, and **Dropout** layers for regularization  
- **Focal Loss** function to handle class imbalance  
- **Advanced Data Augmentation** for improved generalization  
- **Early Stopping** to prevent overfitting  
- Real-time inference with **Streamlit Web App**

 📊 Results

- ✅ **Accuracy:** 96%  
- 📈 Precision, Recall, F1-Score:
  - COVID-19: ~97%
  - Tuberculosis: ~98%
  - Pneumonia: ~94%
  - Normal: ~93%

- 🧪 Evaluated with confusion matrix, classification reports & real-world samples
 
 🌐 Deployment
 
Deployed using **Streamlit**:
- Upload a chest X-ray image (.jpg/.png)
- Model predicts disease class with confidence
- User-friendly web UI for non-technical users

👨‍💻 Authors

- [Afra Jabeen](https://www.linkedin.com/in/afra-jabeen-a00956309/)

📁 Dataset

- [Kaggle Dataset 1](https://www.kaggle.com/datasets/amrutasalagare/lung-disease-dataset)
- [Kaggle Dataset 2](https://www.kaggle.com/datasets/omkarmanohardalvi/lungs-disease-dataset-4-types)

---

> “AI won’t replace doctors, but doctors who use AI will replace those who don’t.”

