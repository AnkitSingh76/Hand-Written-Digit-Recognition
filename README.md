# Hand-Written-Digit-Recognition

A deep learning project for recognizing handwritten digits **(0–9)** using a **Convolutional Neural Network (CNN)** built with TensorFlow/Keras.

## 📌 Dataset

* **Training Images:** 60,000
* **Validation Images:** 6,000
* **Test Images:** 10,000
* **Image Size:** 28 × 28 pixels
* **Image Type:** Grayscale
* **Classes:** 10 (0–9)

## 🧠 CNN Architecture

```text
Input (28×28×1)
      ↓
Conv2D (32 filters, 3×3)
      ↓
MaxPooling2D
      ↓
Conv2D (64 filters, 3×3)
      ↓
MaxPooling2D
      ↓
Flatten
      ↓
Dense (128 neurons)
      ↓
Dropout (30%)
      ↓
Output (10 classes)
```

## ⚙️ Training Configuration

| Parameter        | Value                           |
| ---------------- | ------------------------------- |
| Epochs           | 10                              |
| Batch Size       | 32                              |
| Optimizer        | Adam                            |
| Loss Function    | Sparse Categorical Crossentropy |
| Activation       | ReLU + Softmax                  |
| Dropout          | 0.3                             |
| Validation Split | 10%                             |

## 📊 Results

The CNN was trained for 10 epochs and evaluated on the unseen MNIST test dataset.

| Metric              |   Result |
| ------------------- | -------: |
| Training Accuracy   |     High |
| Validation Accuracy |     High |
| Test Accuracy       | **~99%** |
| Test Loss           |      Low |

The training and validation accuracy/loss were visualized using Matplotlib.

## 🔍 Predictions

The trained model successfully predicts:

* Individual handwritten digit images
* Multiple test images
* Digits from **0 to 9**

The predicted digit is displayed along with the corresponding image.

## 💾 Model Saving

The trained model is saved as:

```text
tf-cnn-model.h5
```

The saved model was successfully loaded and used again for prediction, confirming that the trained model can be reused without retraining.

## 🎯 Learning Outcomes

* Understanding CNN architecture
* Image preprocessing and normalization
* Training and validation of deep learning models
* Model evaluation using accuracy and loss
* Handwritten digit classification
* Saving and loading trained models

## 🛠️ Technologies

**Python | TensorFlow | Keras | NumPy | Matplotlib**


Interested in **Cyber Security, Machine Learning, and Deep Learning**.
