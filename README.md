# Developing a Handwritten Digits Classifier with PyTorch

This project demonstrates how to build and train a neural network for handwritten digit recognition using **PyTorch**, achieving **\~97% accuracy** on the **MNIST dataset**.

It was developed as part of my **AWS-sponsored machine learning journey**, giving me hands-on practice with deep learning concepts, model evaluation, and deployment workflows.

---

## 📖 Why this project?

Handwriting recognition is one of the earliest and most practical applications of deep learning in computer vision. By building this digit classifier, I:

* Gained practical experience with **PyTorch** for model building and training.
* Learned how **preprocessing and normalization** improve training stability.
* Practiced **hyperparameter tuning** to push accuracy above 97%.
* Built a **reusable pipeline** for future OCR projects.

---

## ⚙️ Project Steps

1. **Data Loading**

   * Pulled the MNIST dataset using `torchvision.datasets`.
   * Split into training, validation, and test sets.

2. **Preprocessing**

   * Converted images to tensors.
   * Normalized pixel values to \[-1, 1] for stable learning.

3. **Model Architecture**

   * Implemented a Multi-Layer Perceptron (MLP) with ReLU activations.
   * Used **CrossEntropyLoss** with the **Adam optimizer**.

4. **Training & Validation**

   * Ran for 20 epochs while tracking accuracy and loss.
   * Achieved **\~97% accuracy** on the test set.

5. **Model Export**

   * Saved trained weights with `torch.save()` for future inference.

---

## 📊 Results

| Metric        | Value      |
| ------------- | ---------- |
| Test Accuracy | **97%**    |
| Epochs        | 20         |
| Model Type    | MLP + ReLU |

✅ Training and validation accuracy steadily improved.
✅ Final model successfully reloadable for inference.

---

## 🖼️ Example Predictions

<img width="377" height="244" alt="image" src="https://github.com/user-attachments/assets/70721396-645b-4017-8721-65cdb64fed6d" />


---

## 🚀 Quick Start

Clone this repo and try it yourself:

```bash
# Clone repo
git clone https://github.com/your-username/Developing-a-Handwritten-Digits-Classifier-with-PyTorch.git
cd Developing-a-Handwritten-Digits-Classifier-with-PyTorch

# Install dependencies
pip install -r requirements.txt

# Train the model
python train.py

# Run inference on a sample image
python predict.py sample.png
```

---

## 🔮 Next Steps

* Add **data augmentation** (rotations, shifts) for robustness.
* Experiment with **CNNs** to push accuracy closer to 99%.
* Deploy as an **API** or simple web app (Flask/FastAPI).

---

## 🤝 Acknowledgments

* **AWS** for sponsoring this learning project.
* **Yann LeCun et al.** for releasing MNIST.
* The **PyTorch community** for tutorials and tools.

---

🔥 This version gives you:

* A **catchy intro** with AWS + PyTorch mentioned clearly.
* A **results table** (looks professional).
* A **Quick Start guide** (recruiters/devs love this).
* A spot for visuals (huge for GitHub readability).

---
