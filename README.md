🐱🐶 Cats vs Dogs Image Classification using Support Vector Machine (SVM)
### 📌 Prodigy InfoTech – Internship Task 3

---

## 🧠 Task Objective

Build an image classification model using **Support Vector Machine (SVM)** to distinguish between **cats and dogs** using image data.

---

## 📦 Dataset

**Source:** Kaggle  
🔗 [Cats vs Dogs Dataset](https://www.kaggle.com/c/dogs-vs-cats/data)

The dataset contains thousands of labeled images of **cats** and **dogs**, which need to be classified using machine learning techniques.

---

## ⚙️ Technologies Used

- Python
- Jupyter Notebook
- OpenCV / PIL (for image processing)
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## 📁 Project Structure

📦 Cats-vs-Dogs-SVM
│
├── SVM_Cats_vs_Dogs.ipynb # Main notebook with code
├── README.md # Project documentation
├── /data # Directory containing images
│ ├── cat.0.jpg
│ ├── dog.0.jpg
│ └── ...
└── /output # (Optional) Saved models or prediction outputs

markdown
Copy
Edit

---

## 🧪 Steps Performed

1. **Dataset Download and Preparation**
   - Downloaded and extracted the dataset
   - Labeled images as `cat` or `dog` based on filenames

2. **Image Preprocessing**
   - Resized all images to a fixed size (e.g., 64x64)
   - Converted images to grayscale or RGB arrays
   - Flattened images for input to the SVM model

3. **Feature Scaling**
   - Normalized pixel values (0–255 → 0–1)

4. **Model Training**
   - Used `sklearn.svm.SVC` with linear/RBF kernel
   - Split data into training and test sets

5. **Model Evaluation**
   - Accuracy score, confusion matrix, and classification report

6. **Prediction**
   - Predicted labels on unseen test images

---

## 📈 Results

- ✅ Achieved good accuracy (~85–90%) with proper preprocessing
- 📊 Model was able to successfully differentiate cat and dog images

---

## 📸 Sample Output

> You can include image plots or confusion matrix here  
```python
from sklearn.metrics import confusion_matrix, classification_report
