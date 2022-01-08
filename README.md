# Brain-tumor-detection-CNN Model

### 1. Exploring data:
* Useing  [Brain Tumor Detection 2020 kaggle dataset](https://www.kaggle.com/ahmedhamada0/brain-tumor-detection)
* It consists of 3065 MRI images separated to two classes
      (Tumor – Non-Tumor) brain.

### 2. Data analyzing:
* used cv2.COLOR_RGB2LAB to apply equalization histogram to perceptual lightness.
* Analyzing the histograms, we can deduce that the affected brains have much more perceptual lightness intensity.

### 3. CNN Model:
* Mainly 3 Conv2D layers:
   using maxpooling and activation function as ReLU.
* Flatten, Dense, Activation, Droupout, Dense & Activation.

### 4. Training the model:
* Loss: binary crossentropy as it is used for binary (0 or 1) classification.
* Optimizer: Adam is a replacement optimization algorithm for stochastic gradient descent for training deep learning models that can handle sparse gradients on noisy problems.

### 5. Final result:
* Validation accuracy 97%

[Kaggle Notebook link](https://www.kaggle.com/dinakhalid/brain-tumor-detection)

