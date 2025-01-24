# Multi-Modal Emotion Recognition  

This project is a machine learning-based application for recognizing human emotions using audio and/or video data. The model identifies one of eight possible emotions: **neutral, happy, sad, angry, fearful, disgust, and surprised**.  

---

## Overview  
The **Multi-Modal Emotion Recognition** project leverages both audio and video inputs to classify emotions. By combining data from different modalities, the model aims to improve accuracy and robustness in detecting emotional states.  

---

## Features  
- Recognizes 8 emotions: **neutral, happy, sad, angry, fearful, disgust, surprised**.  
- Supports input from **audio**, **video**, or both.  
- Built using publicly available datasets for training and evaluation.  
- Real-time emotion recognition capability.  

---

## Datasets  
1. **[RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)](https://zenodo.org/record/1188976)**  
   - Contains audio and video recordings with labeled emotions.  
2. **[SAVEE (Surrey Audio-Visual Expressed Emotion)](https://personal.ee.surrey.ac.uk/Personal/P.Jackson/SAVEE/)**  
   - Focused on emotional expressions in speech.  

---

## Technologies Used  
- **Frameworks & Libraries:** TensorFlow, Keras, OpenCV, NumPy, Pandas.  
- **Programming Language:** Python.  
- **Tools:** Matplotlib for visualization, scikit-learn for preprocessing and evaluation.  


## Setup  
### Prerequisites  
- Python 3.8 or above.  
- Install the required libraries:  
  ```bash
  pip install -r requirements.txt
  ```  

### Clone the Repository  
```bash
git clone https://github.com/sifat53/multi-modal-emotion-recognition.git
cd multi-modal-emotion-recognition
```  

---

## Usage  
1. **Preprocess the Data**  
   - Use the provided scripts to preprocess audio and video data from RAVDESS and SAVEE datasets.  
2. **Train the Model**  
   - Run the training script.
3. **Perform Emotion Recognition**  
   - Use the trained model for prediction on new audio/video inputs.

---


## Future Improvements  
- Incorporate additional datasets for better generalization.  
- Optimize the model for real-time inference on edge devices.  
- Experiment with transformer-based architectures for improved accuracy.  


---

## Acknowledgments  
- Special thanks to the creators of the RAVDESS and SAVEE datasets.  
- Inspired by advancements in multi-modal machine learning.  

---

Feel free to contribute or raise issues via pull requests or the [Issues](https://github.com/sifat53/Multi-Modal-Emotion-Recognition/Issues) section!  


