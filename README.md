# DEEPFAKE_IMAGE_DETECTION
Deepfake Image Detection using DCGAN implemented in PyTorch with CelebA Dataset for adversarial learning, fake image generation, and deep learning research.

# 🧠 Deepfake Image Detection using DCGAN

A deep learning project that implements a **Deep Convolutional Generative Adversarial Network (DCGAN)** in **PyTorch** to learn facial image distributions from the CelebA dataset. The project demonstrates adversarial learning through a Generator that creates realistic face images and a Discriminator that learns to distinguish between real and generated images, providing a foundation for deepfake image detection research.

---

## 📌 Project Overview

Deepfake technology has become increasingly realistic, making it difficult to identify manipulated media. This project explores the use of **Generative Adversarial Networks (GANs)** to understand how deepfakes are generated and how neural networks can differentiate between authentic and synthetic facial images.

The model is trained on the **CelebA Face Dataset** using the DCGAN architecture and visualizes the learning process through Generator and Discriminator loss curves.

---

## ✨ Features

* DCGAN implementation using PyTorch
* Automatic dataset loading and preprocessing
* Generator and Discriminator neural networks
* GPU (CUDA) support for faster training
* Adversarial training using Binary Cross Entropy Loss
* Training loss visualization
* Face image generation using random latent vectors
* Modular and well-documented notebook

---

## 🛠️ Tech Stack

| Category                | Technologies         |
| ----------------------- | -------------------- |
| Programming Language    | Python               |
| Deep Learning           | PyTorch, Torchvision |
| Data Processing         | NumPy                |
| Visualization           | Matplotlib           |
| Dataset                 | CelebA Face Dataset  |
| Development Environment | Google Colab         |
| Version Control         | Git & GitHub         |

---

## 📂 Dataset

**Dataset:** CelebA Face Dataset

The CelebA dataset contains thousands of celebrity face images with diverse facial attributes. It is widely used for computer vision and generative deep learning research.

---

## 📁 Repository Structure

```
Deepfake-Image-Detection/
│
├── DEEPFAKE_IMAGE_DETECTION.ipynb
├── README.md
├── LICENSE
├── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Deepfake-Image-Detection.git
```

Navigate to the project directory:

```bash
cd Deepfake-Image-Detection
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

1. Open `DEEPFAKE_IMAGE_DETECTION.ipynb` in Google Colab or Jupyter Notebook.
2. Run all cells sequentially.
3. The notebook will:

   * Download the dataset
   * Preprocess images
   * Train the DCGAN model
   * Generate synthetic face images
   * Display Generator and Discriminator loss curves

---

## 🧠 Model Architecture

### Generator

The Generator converts random noise into realistic facial images using:

* Transposed Convolution Layers
* Batch Normalization
* ReLU Activation
* Tanh Output Layer

### Discriminator

The Discriminator classifies an input image as **Real** or **Fake** using:

* Convolution Layers
* Batch Normalization
* LeakyReLU Activation
* Binary Classification Output

The Generator and Discriminator compete during training, allowing both models to improve iteratively.

---

## 🔄 Project Workflow

1. Load CelebA dataset
2. Preprocess facial images
3. Create DataLoader
4. Build Generator network
5. Build Discriminator network
6. Train using adversarial learning
7. Update Generator and Discriminator weights
8. Monitor training losses
9. Generate realistic face images

---

## 📊 Results

The model successfully learns meaningful facial features through adversarial training.

### Achievements

* Generated realistic human face images
* Learned complex facial representations
* Demonstrated stable Generator and Discriminator training
* Visualized training performance using loss curves

---

## 📊 Model Performance

The model was evaluated after training on the CelebA dataset.

| Metric | Value |
|--------|-------:|
| Training Accuracy | **87.63%** |
| Loss Function | Binary Cross Entropy (BCEWithLogitsLoss) |
| Optimizer | Adam |
| Framework | PyTorch |
| Dataset | CelebA Face Dataset |

The trained DCGAN successfully learned meaningful facial representations and demonstrated high accuracy in distinguishing between real and generated images.

All the sample outputs are present with the code in DEEPFAKE_IMAGE_PREDICTION.ipynb file.

## 💡 Applications

* Deepfake Detection
* Image Forensics
* Face Generation
* AI Research
* Computer Vision
* Digital Media Authentication
* GAN-based Learning

---

## 🚀 Future Improvements

* Improve image quality using StyleGAN
* Add Grad-CAM explainability
* Save trained model weights
* Build a Flask or Streamlit web application
* Support real-time image prediction
* Extend the project to video deepfake detection

---

## 📚 Learning Outcomes

This project strengthened my understanding of:

* Generative Adversarial Networks (GANs)
* Deep Convolutional Neural Networks
* Image preprocessing
* Binary classification
* Adversarial learning
* PyTorch model implementation
* Deep learning workflows

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👩‍💻 Author

**Khushi Chamoli**

---

