# 🎨 AI Drawing Generator with GAN

This repository contains an implementation of an **AI Drawing Generator** using **pre-trained Generative Adversarial Networks (GANs)** such as **DCGAN** or **SketchRNN** to generate **simple patterns, handwritten digits, or sketches**. The project is implemented in **Google Colab** for ease of GPU access and reproducibility.



## 📑 Table of Contents

* [Introduction](#introduction)
* [Dataset](#dataset)
* [Objectives](#objectives)
* [Technologies Used](#technologies-used)
* [Installation](#installation)
* [Usage](#usage)
* [Model Overview](#model-overview)
* [Results and Samples](#results-and-samples)
* [Project Structure](#project-structure)
* [Future Work](#future-work)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)



## 📝 Introduction

Generative Adversarial Networks (GANs) are widely used for generating **realistic images, sketches, and patterns**. This project demonstrates how pre-trained GAN models can be leveraged to create **drawings and sketches** efficiently for learning and creative AI applications.



## 🎯 Objectives

✅ Implement a **pre-trained GAN model (DCGAN or SketchRNN)** in Google Colab

✅ Generate simple patterns or sketches (e.g. handwritten digits, quickdraw sketches)

✅ Visualize generated outputs

✅ Provide an accessible learning notebook for GAN-based drawing generation



## 📚 Dataset

* **For DCGAN:** MNIST dataset for handwritten digits
* **For SketchRNN:** Google Quick, Draw! dataset for simple sketches
* **Source:**

  * MNIST: [Yann LeCun’s MNIST Database]()
  * Quick, Draw!: [Google Quick, Draw! Dataset]()



## ✨ Features

* Uses **pre-trained GAN weights** for quick generation
* Generates **handwritten digits, patterns, or simple sketches**
* Provides clear and modular Google Colab code
* Visualizes generated samples with **Matplotlib**



## 🛠️ Technologies Used

* **Python 3**
* **TensorFlow / PyTorch**
* **Google Colab**
* **Matplotlib**
* **NumPy**



## ⚙️ Installation

No local installation required if using **Google Colab**.

### 🔗 Google Colab

1. Click [here](#) to open the notebook in Google Colab.
2. Connect to a GPU runtime for faster generation.
3. Run cells sequentially to load models and generate samples.

### 💻 Local Installation (optional)

If running locally:

```bash
git clone https://github.com/yourusername/AI_Drawing_Generator_with_GAN.git
cd AI_Drawing_Generator_with_GAN
pip install -r requirements.txt
python gan_generator.py
```



## ▶️ Usage

1. Open the **Colab notebook**.
2. Run cells to:

* Import libraries
* Load pre-trained DCGAN or SketchRNN models
* Generate samples
* Visualize outputs

3. *(Optional)* Modify latent vector input to control generation variability.



## 🧠 Model Overview

* **DCGAN:** Generates handwritten digits from random noise vectors trained on MNIST.
* **SketchRNN:** Generates sequential vector sketches trained on Quick, Draw! dataset.



## 📊 Results and Samples

### 🎨 Generated Handwritten Digits (DCGAN)

*(samples)*

### ✏️ Generated Sketches (SketchRNN)

*(samples)*



## 📁 Project Structure

```
AI_Drawing_Generator_with_GAN/
 ┣ models/
 ┃ ┗ pre_trained_dcgan.pth
 ┣ notebooks/
 ┃ ┗ AI_Drawing_Generator_with_GAN.ipynb
 ┣ requirements.txt
 ┣ gan_generator.py
 ┗ README.md
```



## 💡 Future Work

* Fine-tune GAN models on custom drawing datasets
* Extend to **image-to-image translation GANs** (Pix2Pix, CycleGAN) for sketch-to-photo applications
* Build a **Streamlit web app** for interactive AI drawing generation
* Experiment with **StyleGAN** for more realistic and high-resolution outputs



## 🤝 Contributing

Contributions are welcome to enhance models, add more datasets, or build app integrations!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to your branch (`git push origin feature/YourFeature`)
5. Open a pull request



## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.



## 📬 Contact

**Ugama Benedicta Kelechi**
[LinkedIn](www.linkedin.com/in/ugama-benedicta-kelechi-codergirl-103041300) | [Email](mailto:ugamakelechi501@gmail.com) | [Portfolio](#)



### ⭐️ If you find this project insightful, please give it a star and share with deep learning and generative AI learners!

