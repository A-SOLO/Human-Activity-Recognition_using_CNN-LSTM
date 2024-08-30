# Human-Activity-Recognition_using_CNN-LSTM
Developed and implemented deep learning models for human activity recognition, focusing on spatiotemporal data processing and sequence modeling.

# Model Development: 
* Implemented a ConvLSTM model to capture spatiotemporal dynamics by integrating convolutional and LSTM layers.
  
![download_arch_1](https://github.com/user-attachments/assets/21f5a88f-7e82-402a-be8e-82b9309a89e4)


* Additionally, developed an LRCN model combining CNNs for spatial feature extraction and LSTM layers for temporal sequence modeling.

![download_arch_2](https://github.com/user-attachments/assets/ad66962d-198a-4070-8396-eaee51ea0c79)

  
# Data Pipeline:
* Preprocessed the UCF50 dataset, including frame extraction, resizing, normalization, and conversion to fixed-length sequences to ensure consistent input for training.
  
# Model Training & Optimization:
* Trained models using categorical cross-entropy loss and Adam optimizer, with early stopping callbacks to prevent overfitting.
* The ConvLSTM model was trained over 50 epochs with recurrent dropout, while the LRCN model was trained over 70 epochs with dropout layers after each convolutional block.
  
# Performance Evaluation:
* Achieved an accuracy of 82.27% with the ConvLSTM model and 89.49% with the LRCN model on the test set, demonstrating the effectiveness of both models in human activity classification.
