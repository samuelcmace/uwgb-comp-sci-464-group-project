# ✅ Test MNIST Model with Your Own Handwritten Digits

- **Due:** Sunday, December 7th, 2025 by 11:59 PM
- **Points:** 10
- **Submission Type:** Text Entry or File Upload
- **Allowed Attempts:** 2

**Notebook Provided:**
`Digit_recognition_using_Neural_Network.ipynb`

---

## 📌 Task 1 (2 points): Comparing Networks

Compare the accuracy of:

* The **Convolutional Neural Network (CNN)**
* **Dense Neural Networks** with:

  * 1 hidden layer
  * 2 hidden layers
  * 3 hidden layers
  * 4 hidden layers
* Each dense network uses **512 nodes per layer** and **ReLU activation**.

### ✅ Requirements:

* Produce a **plot with five curves**:

  * 1 for the CNN
  * 1 for each dense network (1–4 hidden layers)
* **X-axis:** Number of epochs
* **Y-axis:** Test accuracy
* Plot the **first 10 epochs only**
* **Explain the results**, including:

  * Why some models perform better or worse than others
  * Observed accuracy trends

---

## 📌 Task 2 (2 points): Comparing Activation Functions

Compare **ReLU vs Sigmoid** activation functions in the *same CNN*.

### ✅ Requirements:

* Modify the CNN to use **sigmoid activation**
* Produce a **single plot with two curves**:

  * One for **ReLU**
  * One for **Sigmoid**
* **X-axis:** Number of epochs
* **Y-axis:** Test accuracy
* Plot the **first 10 epochs only**
* **Explain the results**, including:

  * Why one activation function outperformed the other

---

## 📌 Task 3 (2 points): The Value of Dropout

Compare CNN performance **with and without dropout**.

### ✅ Requirements:

* Toggle **dropout ON and OFF** in **all Conv2D layers**
* Produce **two separate graphs**:

  1. **Training Accuracy**
  2. **Test Accuracy**
* Each graph must contain:

  * One curve **with dropout**
  * One curve **without dropout**
* **X-axis:** Number of epochs
* **Y-axis:** Accuracy
* Run **up to 100 epochs**

  * No marks deducted for fewer epochs
  * You **must explain**:

    * Expected trends as epoch count approaches 100
    * Whether results match theoretical expectations

---

## 📌 Task 4 (4 points): Personal Handwriting Evaluation

### ✅ Exercise:

* Create your **own handwritten digits**
* Test them using your **trained MNIST model**
* Analyze:

  * Correct predictions
  * **Incorrect predictions**
  * Why misclassifications may have occurred

---

## 📤 Submission Instructions

* Submit **one Python Notebook** containing:

  * All completed tasks
  * All plots
  * All written explanations
