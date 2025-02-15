# 🌟 Count-Face-Video 🎥😊

Welcome to **Count-Face-Video**! 🚀 This project brings the magic of **Facial Recognition** into action, identifying and tracking faces in videos with the power of **PCA & KNN**. Let's dive into AI & Computer Vision with a bright smile! 😃✨

---

## 🎯 Overview
The AI-powered system detects, identifies, and counts faces in videos. Leveraging **Principal Component Analysis (PCA)** and **K-Nearest Neighbors (KNN)**, this project processes video files to track face occurrences over time. 🤖📊

---

## 🔄 Project Workflow 📌
1️⃣ **Training Phase** 📚: Process dataset images, apply PCA and train KNN classifier.

2️⃣ **Detection Phase** 🎥: Read video frames, detect faces, classify identities.

3️⃣ **Result Analysis** 📊: Save detection results in `output.txt` with timestamps.  

---

## 📂 Project Structure 🏗️
```
📁 Count-Face-Video/
├── 📂 dataset/                             # Dataset containing subfolders for each person
├── 📄 haarcascade_frontalface_default.xml  # Haar Cascade model for face detection
├── 📄 face_recognition_model.pkl           # Trained PCA + KNN model
├── 📓 Train and Detect.ipynb               # Jupyter Notebook for training & detection
├── 🎥 drstrange_.mp4                       # Video file for face detection
├── 📄 output.txt                           # Detection results with timestamps
```

---

## ✨ Features
✅ Detect & recognize faces using **Haar Cascade + PCA + KNN**.

✅ Process video files and track face occurrences over time.

✅ Log results with timestamps to monitor face appearances.

✅ Lightweight and easy to use! ⚡

---

## 🛠 Technologies & Libraries
🔹 **Python** 🐍  
🔹 **OpenCV** 👀  
🔹 **NumPy** 🔢  
🔹 **Scikit-learn** 🧠  
🔹 **Pickle** 📦  

---

## 🚀 Installation
Ensure you have Python installed, then install dependencies:
```sh
pip install opencv-python numpy scikit-learn pickle-mixin
```

---

## 🎬 Usage
### 🏗 Training the Model and Running Face Detection on a Video 🎥
Run the Jupyter Notebook to train the facial recognition model:
```sh
jupyter notebook Train and Detect.ipynb
```

---

## 📊 Result and Findings
The detection results are stored in `output.txt`, showing occurrences with timestamps:
```
ben detected 560 times
Appears in time:
0 minute 0 second
0 minute 1 second
...
eli detected 39 times
Appears in time:
0 minute 0 second
0 minute 1 second
...
```

---

## 🚀 Future Improvements 🔮
✨ Implement deep learning-based recognition (e.g., **CNN**).

✨ Improve accuracy using additional feature extraction techniques.

✨ Add real-time video streaming support.  

---

## 🤝 Contributing 🌍
Contributions are welcome! If you'd like to improve the project:  

1️⃣ **Fork the repository** 🍴

2️⃣ **Create a new branch** 🌱  

3️⃣ **Make your improvements** ✨

4️⃣ **Submit a pull request** 🔄  

*🌟 If you love this project, don't forget to **star ⭐ the repository** and contribute! 🙌* 

---
**💖 Happy Coding & Keep Innovating! 💖 ✨**
