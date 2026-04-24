# Cat-vs-Dog-Image-Classification-using-SVM
An image classification project using Support Vector Machine (SVM) to classify cats and dogs from the Kaggle dataset.
# 🐶🐱 Cat vs Dog Image Classification using SVM

## 📌 Project Overview

This project uses a Support Vector Machine (SVM) model to classify images of cats and dogs from a dataset. The model is trained using image features extracted from resized grayscale images.

---

## 🎯 Objective

To build an image classification system that can distinguish between cats and dogs.

---

## 📂 Dataset

Dataset used: Dogs vs Cats dataset from Kaggle

Images are organized into:

* cats/
* dogs/

---

## ⚙️ Technologies Used

* Python
* OpenCV
* NumPy
* Scikit-learn

---

## 🔄 Workflow

1. Load images from dataset
2. Resize images (64x64)
3. Convert to grayscale
4. Flatten images into feature vectors
5. Train SVM classifier
6. Evaluate accuracy
7. Predict new images

---

## 🧠 Algorithm Used

### Support Vector Machine (SVM)

SVM is a supervised learning algorithm used for classification tasks by finding the optimal decision boundary between classes.

---

## ▶️ How to Run

### Install dependencies:

```bash id="x3pxpf"
pip install opencv-python numpy scikit-learn
```

### Run program:

```bash id="0j7dva"
python svm_cats_dogs.py
```

---

## 💻 Example

Input:
Enter image path to test: dog.jpg

Output:
Prediction: Dog 🐶

---

## 🚀 Future Enhancements

* Use color features instead of grayscale
* Try different kernels (RBF)
* Use deep learning (CNN) for better accuracy

---

## ⚠️ Limitations

* Low accuracy compared to deep learning
* Sensitive to image size and quality

---

## 📚 Conclusion

This project demonstrates how SVM can be applied to image classification tasks using basic image processing techniques.

---
