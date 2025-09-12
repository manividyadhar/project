# Automated ECG Classification Using Deep Learning  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1jYF-aP9XbZx_AAhEPua2Qm5XzXqZnGcO)  
![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)  
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)  
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-CNN%20%2B%20PSO-brightgreen)  
![Dataset](https://img.shields.io/badge/Dataset-MIT--BIH-red)  

---

This project presents a **novel deep learning framework** for automated ECG (Electrocardiogram) classification, integrating **Particle Swarm Optimization (PSO)** with **Convolutional Neural Networks (CNNs)**. The system automatically optimizes CNN hyperparameters, eliminating the need for manual tuning, and achieves high accuracy in detecting and classifying cardiac arrhythmias.  

📌 **Google Colab Notebook**: [Run the Code Here](https://colab.research.google.com/drive/1jYF-aP9XbZx_AAhEPua2Qm5XzXqZnGcO)  

---

## ✨ Features
- Automated optimization of CNN architecture using **PSO**.  
- Classification of **five types of cardiac arrhythmias** from ECG signals.  
- Achieves **99.25% accuracy** on the MIT-BIH Arrhythmia dataset.  
- Eliminates manual feature engineering by leveraging deep learning.  
- Suitable for **real-time applications** such as wearable devices and telemedicine.  

---

## 📊 Dataset
We use the **MIT-BIH Arrhythmia Dataset**, which includes:  
- 48 half-hour recordings from 47 subjects.  
- Digitized at 360 samples per second per channel.  
- Contains annotations for normal and arrhythmic beats.  

👉 Dataset link: [MIT-BIH Arrhythmia Database](https://www.physionet.org/content/mitdb/1.0.0/)  

---

## ⚙️ Workflow
1. **ECG Data Acquisition** – Raw signals are collected from the MIT-BIH dataset.  
2. **Preprocessing** – Noise removal, normalization, and segmentation of heartbeats.  
3. **Model Training** – CNN optimized with PSO for automatic hyperparameter selection.  
4. **Evaluation** – Accuracy, precision, recall, F1-score, ROC curves, and confusion matrices.  

---

## 🚀 Results
- **Accuracy**: 99.25%  
- **Precision, Recall, F1-Score**: ~0.99 across all arrhythmia types.  
- **AUC (ROC Curve)**: 1.0 (perfect classification performance).  
- Outperforms traditional ML models (SVM, KNN, etc.) and baseline CNNs.  

---

## 📂 Project Structure
📦 Automated-ECG-Classification
┣ 📜 README.md
┣ 📜 paper_writeup.docx # Research paper writeup
┗ 🔗 Colab Notebook (link above)


---

## 🛠️ Technologies Used
- **Python 3.9**  
- **TensorFlow / Keras**  
- **NumPy, Pandas, Matplotlib**  
- **Google Colab**  
- **MIT-BIH Dataset**  

---

## 📖 Reference Paper
This project is based on the paper:  

> **Automated ECG Classification Using Deep Learning Framework**  
> Authors: Ms. M. Anitha, Ms. K. Baby Ramya, Mr. N. Mani Vidyadhar  
> Published at SRK Institute of Technology, Vijayawada.  

---

## 👨‍💻 Contributors
- **N. Mani Vidyadhar** (Student, MCA Department, SRKIT)  
- **Ms. K. Baby Ramya** (Assistant Professor, SRKIT)  
- **Ms. M. Anitha** (Assistant Professor & HOD, SRKIT)  

---

## 📬 Contact
For queries, reach out at:  
- 📧 manividyadhar143@gmail.com  
- 📧 kramyababy19k@gmai.com  
- 📧 anitha3harshak@gmail.com  
