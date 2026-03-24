# MLP-Image-Classification-CIFAR-10
An optimized MLP classifier is developed for CIFAR-10 through careful selection of hyperparameters. The approach emphasizes practical design decisions without using automated tuning methods.

## 🎯 **Objective**

To design an **optimal MLP classifier** for CIFAR-10 using **heuristic-based hyperparameter selection**, without using grid search, random search, or automated tuning techniques.

---

## 🗂 **Dataset**

* **CIFAR-10 color image dataset**
* 50,000 training images
* 10,000 test images
* Image size: 32 × 32 × 3
* Number of classes: 10

---

## 🧠 **Model Architecture**

* **Hidden layers:** 3

  * 512 → 256 → 128 neurons
* **Activation:** ReLU
* **Weight initializer:** He Normal
* **Optimizer:** SGD with momentum (0.9)
* **Learning rate:** 0.01

---

## 🛡 **Regularization Techniques**

* Dropout (rate = 0.3)
* L2 weight decay (0.0001)
* Early stopping (patience = 10)

---

## 📊 **Evaluation Metrics**

* Training accuracy
* Test accuracy
* Confusion matrix
* Classification report
* Accuracy & loss learning curves

---

## 🧩 **Heuristic Design Insights**

* CIFAR-10 complexity requires **deep architectures + strong regularization**
* ReLU + He Normal mitigated vanishing gradient issues
* Dropout and L2 were critical to generalization
* MLP limitations observed due to lack of spatial awareness (CNNs are better suited)

---

## 🛠 **Technology Stack**

* **Language:** Python 3.x
* **Libraries:**

  * TensorFlow / Keras
  * NumPy
  * Matplotlib
  * Scikit-Learn
* **Environment:** Jupyter Notebook

---

## 📄 **Report**

A complete written report containing:

* Experimental tables
* Learning curves
* Analytical answers (Q1–Q9)
* Model evaluation metrics

---

## ✅ **Notes on Academic Integrity**

* No automated hyperparameter tuning methods were used
* Heuristics were selected based on empirical results and established ML practices
* AI tools were used cautiously and critically evaluated, as documented in the report
