# AMD Prediction Using Retinal Fundus Images

This project uses deep learning to predict **Age-related Macular Degeneration (AMD)** from retinal fundus images. A Convolutional Neural Network (CNN) is trained on a binary classification task to distinguish between AMD-affected and normal eyes.

## About Age-related Macular Degeneration (AMD)

**Age-related Macular Degeneration (AMD)** is a progressive eye condition that affects the **macula**, the part of the retina responsible for central vision. It is a **leading cause of vision loss in adults over 50** and can significantly impact quality of life by making it difficult to read, drive, recognize faces, or perform tasks requiring fine vision.

### Types of AMD

1. **Dry AMD (Atrophic):**
   - Most common form (~85–90% of cases)
   - Caused by thinning of macular tissue over time
   - Slower progression but currently no cure

2. **Wet AMD (Neovascular or Exudative):**
   - Less common but more severe
   - Caused by abnormal blood vessels under the retina
   - Leads to rapid vision loss but is treatable with anti-VEGF injections

### Risk Factors
- Age (50+)
- Family history
- Smoking
- High blood pressure
- Obesity
- Sunlight exposure

### Symptoms
- Blurred or distorted vision
- Straight lines appear wavy (metamorphopsia)
- Difficulty recognizing faces
- Dark or empty areas in central vision

### Importance of Early Detection

Early detection of AMD is crucial for preventing severe vision loss. Regular retinal screenings help monitor disease progression. AI-powered tools like this project aim to **automate AMD detection from retinal images**, making diagnosis **faster, cheaper, and scalable**, especially in resource-limited settings.



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

## Research Paper

You can read the full research paper related to this project here:

 [Click to View Paper](https://www.overleaf.com/read/jngmjcdvswkr#c29193)



## Author

**Tushar Jain**  
tusharjain123.97@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/tushar-jain-296296296?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)




