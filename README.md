# AMD Prediction Using Retinal Fundus Images

This project uses deep learning to predict **Age-related Macular Degeneration (AMD)** from retinal fundus images. A Convolutional Neural Network (CNN) is trained on a binary classification task to distinguish between AMD-affected and normal eyes.



## Project Structure


## Dataset

- Total Images: 1,556
  - AMD: 778 images
  - Normal: 778 images
- Image Preprocessing: Resizing, normalization
- Split:
  - Training: 80%
  - Validation: 10%
  - Test: 10%


## Model Architecture

Custom CNN with:
- Convolutional layers + ReLU
- BatchNormalization
- MaxPooling
- Flatten → Dense layers
- Dropout to reduce overfitting
- EarlyStopping to halt on convergence



## Performance Metrics

Evaluated using:
- Accuracy
- Confusion Matrix
- Precision, Recall, F1-score (via Classification Report)



