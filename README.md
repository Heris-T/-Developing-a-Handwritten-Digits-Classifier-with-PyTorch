# Developing-a-Handwritten-Digits-Classifier-with-PyTorch
A PyTorch project to build and train a handwritten digit classifier on the MNIST dataset, sponsored by AWS.

# Developing a Handwritten Digits Classifier with PyTorch

This project is a proof of concept for **optical character recognition (OCR)**, using the classic **MNIST dataset** of handwritten digits.  
The goal was to design, train, and evaluate a neural network that can correctly identify digits from 0–9.

> 🚀 Sponsored by **AWS** as part of my machine learning engineering journey.

---

## 📖 Why this project?
Handwriting recognition is one of the earliest and most practical applications of deep learning in computer vision.  
By building a digit classifier:
- I got hands-on experience with **PyTorch** for model building and training.  
- I learned how preprocessing and normalization improve learning stability.  
- I practiced hyperparameter tuning to push model accuracy above **97%**.  
- I built a reusable pipeline for future OCR-related projects.  

---

## ⚙️ Project Steps
1. **Data Loading**  
   - Downloaded MNIST dataset via `torchvision.datasets`.
   - Split into training, validation, and test sets.

2. **Preprocessing**  
   - Converted images to tensors.  
   - Normalized pixel values to [-1, 1] for stable training.

3. **Model Architecture**  
   - Implemented a Multi-Layer Perceptron (MLP) with ReLU activations.  
   - Used `CrossEntropyLoss` and the **Adam** optimizer.

4. **Training & Validation**  
   - Tracked accuracy and loss over 20 epochs.  
   - Achieved **~97% test accuracy**.

5. **Saving the Model**  
   - Exported trained weights with `torch.save()` for reuse.

---

## 📊 Results
- ✅ Training and validation accuracy steadily improved.  
- ✅ Final **test accuracy: ~97%**.  
- ✅ Model successfully saved and reloadable for future inference.

---

## 🖼️ Example Predictions
(You can add screenshots of predictions or a confusion matrix here.)

---

## 🔮 Next Steps
- Add **data augmentation** (rotations, shifts) to handle more real-world handwriting styles.  
- Experiment with **CNNs** (Convolutional Neural Networks) to push accuracy closer to 99%.  
- Deploy model as an **API** or simple web app.

---

## 🤝 Acknowledgments
- **AWS** for sponsoring this project.  
- **Yann LeCun et al.** for releasing the MNIST dataset.  
- **PyTorch** community for tools and tutorials.

---
