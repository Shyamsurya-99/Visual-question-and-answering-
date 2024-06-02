# mVQA Code Files

This repository contains multiple Visual Question Answering (VQA) models applied to a medical dataset. The models use different architectures for feature extraction from images and text. The dataset and the required code files are organized as follows:

## Code Files

The repository consists of 5 code files:

### PyTorch Code Files

1. **vgg16_reset50_BiLSTM.ipynb**
   - Uses In-Built VGG16 & ResNet50 for extracting image features.
   - Uses Bi-directional LSTM (BiLSTM) for extracting text features.

2. **cnn_BiLSTM.ipynb**
   - Uses a custom Convolutional Neural Network (CNN) for extracting image features.
   - Uses BiLSTM for extracting text features.

3. **cnn_BiLSTM_MHAM.ipynb**
   - Uses a custom CNN for extracting image features.
   - Uses BiLSTM with Multi-Head Attention Mechanism (MHAM) for extracting text features.

4. **cnn_LSTM_SAM.ipynb**
   - Uses a custom CNN for extracting image features.
   - Uses LSTM with Self-Attention Mechanism (SAM) for extracting text features.

### TensorFlow Reference Code File

5. **A_16_mVQA_tensor.ipynb**
   - Reference code file that includes all the above models executed in a single file using TensorFlow library.

## Dataset

The dataset required for executing the above codes is provided in the `A_16_mQVA_Dataset` folder. This folder consists of:
- A `.csv` file containing metadata and labels.
- A folder containing radiology images of brain, chest, and abdomen.

The dataset can also be accessed and downloaded from Kaggle using the following link:
[VQA-RAD: Visual Question Answering Radiology](https://www.kaggle.com/datasets/mdzeeshanhassan/vqa-rad-visual-question-answering-radiology)

## Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/A_16_mVQA.git
   cd A_16_mVQA
2 Run the notebook as per your requirement:
  ```bash
jupyter notebook vgg16_reset50_BiLSTM.ipynb
# or any other notebook

