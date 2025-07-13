# Fruit Image Classifier 🍎🍌
## Project Overview :
This project uses a pre-trained image classification model created with **Teachable Machine**, then exported and tested using **TensorFlow** in Python.
The goal is to classify images of fruits – specifically **apple** and **banana** – and display prediction results with confidence scores.
## Project Files :
- `keras_model.h5` –> Trained model exported from Teachable Machine
- `labels.txt` –> Class labels (Apple, Banana)
- `model_predict_fruit.py` –> Python script to load model and predict
- `apple_test.jpg` –> Example Apple image
- `banana_test.jpg` –> Example Banana image
- `apple_result.png` -> Screenshot of apple prediction result 
- `banana_result.png` -> Screenshot of banana prediction result 
- `README.md` -> Project description
## How to Run ?
1. Open `model_predict_fruit.py` in Google Colab or local Python environment.
2. Make sure all files are in the same directory or mounted in `/content/drive/MyDrive/converted_keras/`.
3. Run the script. It will:
   - Load the model  
   - Predict results for both images  
   - Print prediction confidence  
   - Display the predicted images with titles
## Requirements :
Make sure to install the correct versions of TensorFlow and Keras before running the script (especially in Google Colab):
```bash
pip install tensorflow==2.15.0 keras==2.15.0

## Author :
  Made By: **Sura Abdullah Alkhuzaim**
