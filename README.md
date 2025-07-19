# Sinhala Sign Language Classification Using Deep Learning

This project focuses on the classification of Sinhala Sign Language using deep learning models. It includes data augmentation, model training with various architectures, cross-validation, and real-time sign detection through webcam integration. 

---

## 📁 Project Structure

### 🔄 1. Data Augmentation
- **`ASLDataAug.ipynb`**  
  Implements data augmentation techniques to enhance the size and diversity of the training dataset.

### 📊 2. Model Performance Visualization
- **`SinhalaSignalnGraph.ipynb`**  
  Generates training and validation accuracy/loss curves for various trained models.

### 🧠 3. Model Training (Direct Training)
- **`directcodemobilenet.ipynb`**  
  Trains a MobileNet model on the sign language dataset.

### 🔁 4. Cross-Validation Experiments
Training and evaluation using k-fold cross-validation with multiple CNN architectures:
- **`mobilenetasl.ipynb`** – MobileNet  
- **`inceptionv3asl.ipynb`** – InceptionV3  
- **`densnenet121asl.ipynb`** – DenseNet121  
- **`aslcrossval201.ipynb`** – DenseNet201

### 🎥 5. Real-Time Sign Language Detection (Webcam)
- **`ASLdemoWebcam.ipynb`**  
  Uses a trained ASL model to detect and predict signs using live webcam feed.  
- **`SinhalaDemoWebCam.ipynb`**  
  Real-time sign recognition for Sinhala sign language using a webcam.

### 🎥 6. Evaluate web cam predictions using SHAP plot
- **`SHAPoutput.ipynb`**  
 for American Sign Language dataset.  
- **`SinhalaSignLanguage.ipynb`**  
  for Sinhala sign language dpi=680(dots per inch) because need to get clear SHAP plots.

---

## 📈 Model Explainability (Optional)
SHAP (SHapley Additive exPlanations) can be integrated with the webcam prediction notebooks to interpret model predictions.

---

## 💡 Technologies Used
- TensorFlow / Keras
- OpenCV
- SHAP (for model explainability)
- NumPy, Pandas, Matplotlib

---

## 📌 Note
This repository is designed for research and educational purposes. Make sure to install all required dependencies before running the notebooks.

---

## ✍️ Authors
H.M.Lihini Sangeetha
H.M. Gammulle

---

## 📜 License
This project is licensed under the MIT License.

