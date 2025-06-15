# Homeassignment3
Home-assignment-3
Neural Networks Assignment – Feature Extraction & Data Preprocessing

University: University of Central Missouri
Course: Neural Networks and Deep Learning
Term: SUMMER 2025
Student Name: Santhosh Reddy Kistipati
Student ID: 700776947


Esily can accuss the github link :"https://github.com/santhoshK12/Homeassignment3/tree/main"

 How to Run Each Program (All 5 Questions) in Google Colab

Follow the below process for each program to run it successfully in Google Colab:

---

###  Q1: Implementing an RNN for Text Generation using LSTM

**Steps:**
1. Run the initial imports cell (TensorFlow, NumPy, etc.).
2. A text dataset (e.g., "The Little Prince" or any input text) is loaded.
3. Preprocessing: Convert text into character sequences.
4. Build the model using `tf.keras.Sequential` with LSTM layers.
5. Compile and train the model using the dataset.
6. Generate new text using a seed sequence and `model.predict()`.

**In Colab:**
- Run all cells under Question 1 in order.
- Wait for training to complete.
- Scroll to bottom to view the generated text output.

---

###  Q2: Autoencoder (Basic and Denoising)

#### Part 1: Basic Autoencoder
1. Load MNIST dataset using `tensorflow.keras.datasets`.
2. Normalize the pixel values.
3. Define encoder and decoder using Dense layers.
4. Train the model with `model.fit()`.
5. Reconstruct test images and show comparisons using `matplotlib`.

#### Part 2: Denoising Autoencoder
1. Add random Gaussian noise to MNIST input images.
2. Use same encoder-decoder structure.
3. Train on noisy images but output clean images.
4. Display noisy input vs. denoised output.

**In Colab:**
- Run Part 1 cells first.
- Then run Part 2 cells.
- Output images will be shown in plots.

---

### Q3: CNN for Image Classification using CIFAR-10

**Steps:**
1. Import CIFAR-10 dataset via `torchvision.datasets`.
2. Normalize images using `transforms.Compose`.
3. Use `DataLoader` for batching.
4. Define CNN model with `nn.Conv2d`, `ReLU`, `MaxPool2d`, and `Linear`.
5. Train model with optimizer (e.g., SGD) and loss function.
6. Evaluate accuracy on test set.

**In Colab:**
- Run preprocessing and data loading cells.
- Run model architecture and training loop cells.
- Run evaluation cell to view accuracy.

---

### Q4: Transfer Learning using ResNet18

**Steps:**
1. Load pre-trained ResNet18 using `torchvision.models`.
2. Modify final `fc` layer to classify CIFAR-10 (10 classes).
3. Define optimizer and loss function.
4. Train model for few epochs.
5. Evaluate and print test accuracy.

**In Colab:**
- Run ResNet model loading and modifying cells.
- Train the model and evaluate performance.
- Outputs will be printed at the end.

---

###  Q5: Comparative Analysis and Conclusion

**Steps:**
1. Compare model performance (accuracy, loss, etc.).
2. Analyze results from Q1 to Q4.
3. Print conclusion or summary of findings.
4. Optionally visualize comparison using graphs.

**In Colab:**
- Run final conclusion and summary cells.
- Make sure all prior model outputs are available for valid comparisons.

---


