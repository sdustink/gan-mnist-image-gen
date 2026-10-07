# gan-mnist-image-gen

Generating synthetic overhead images of **oil and gas fields** and **stadiums** using a custom Generative Adversarial Network (GAN) architecture. The project focuses on developing a GAN from scratch and improving its image generation quality through hyperparameter tuning.

## 📊 Dataset

* **Dataset:** Overhead MNIST
* **Selected Classes:** Oil and Gas Field, Stadium
* **Type:** Overhead satellite/aerial imagery
* The dataset was filtered to focus specifically on the **oil and gas field** and **stadium** classes for GAN-based image generation.

## ⚙️ Methodology

1. Load and preprocess the selected Overhead MNIST classes.
2. Prepare training images for GAN-based generation.
3. Design a **custom GAN architecture** consisting of a Generator and Discriminator.
4. Train the baseline GAN model to generate synthetic overhead images.
5. Perform **hyperparameter tuning** to optimize GAN training performance.
6. Generate synthetic images using the modified GAN configuration.
7. Evaluate image generation quality using the **Fréchet Inception Distance (FID)**.

## 📈 Results

Hyperparameter tuning improved the quality of generated images based on FID:

| Model        |          FID |
| ------------ | -----------: |
| Baseline GAN |     310.7437 |
| Modified GAN | **248.2988** |
| Improvement  |  **62.4450** |

The modified GAN achieved a lower FID score, indicating improved similarity between the generated images and the real image distribution.

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook

## 📂 Project Structure

```text
├── main.ipynb
└── README.md
```


