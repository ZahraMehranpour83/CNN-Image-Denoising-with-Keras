CNN Image Denoising with Keras

📌 Introduction

This project implements a Convolutional Neural Network (CNN) inspired by U-Net architecture to remove noise from images in the MNIST dataset. The workflow involves adding Gaussian noise to clean images and then training the model to reconstruct the original, noise-free images.


---

📂 Project Structure

1. Data Loading – Load MNIST dataset from Keras.


2. Noise Addition – Add Gaussian noise using the add_noise function.


3. Model Construction – Build an encoder-decoder style CNN model.


4. Model Training – Train the model using noisy images as input and clean images as labels.


5. Results Visualization – Compare noisy input images with denoised outputs.




---

⚙ Requirements

Install the following dependencies before running the code:

pip install numpy matplotlib tensorflow


---

🚀 
How to Run

1. Open the CNN_DENOIS.ipynb notebook.


2. Run all the cells sequentially.


3. At the end, the notebook will display side-by-side comparisons of noisy and denoised images.




---

📊 Example Output

The model takes a noisy image as input and produces a denoised version.

Noisy Input	Denoised Output

	



---

🧠 Applications

Preprocessing images for better analysis.

Improving quality of medical, satellite, and scanned document images.

Training more robust models in noisy environments.
