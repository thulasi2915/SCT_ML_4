# SCT_ML_4

##  Task: Hand Gesture Recognition using CNN

###  Description  
This project develops a **Convolutional Neural Network (CNN)** model to accurately identify and classify different hand gestures from image data.  
The goal is to enable **gesture-based human-computer interaction** for intuitive control systems.


###  Objective  
- Build and train a CNN model for recognizing hand gestures.  
- Classify images into 20 gesture categories.  
- Evaluate performance using accuracy and visual predictions.


### Technologies & Libraries Used  
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- OpenCV  
- Scikit-learn  


###  Steps Performed  
1. Import libraries and load hand gesture dataset.  
2. Preprocess images (resize, normalize, augment).  
3. Split data into training and validation sets.  
4. Build CNN model using Conv2D, MaxPooling, Flatten, Dense layers.  
5. Train and evaluate the model on gesture dataset.  
6. Save trained model (`hand_gesture_model.h5`).  
7. Test model on new images to predict gesture class.


###  Output  
- Model accuracy and loss graph  
- Sample image predictions with gesture class  
- Trained CNN model file for reuse  


###  Dataset  
The dataset contains images of **20 different hand gestures**, stored in subfolders (0–19), each representing a distinct gesture class.  
Example folder structure:

test/
├── 0/
├── 1/
├── 2/
...
└── 19/

###  How to Run  
```python
# 1️⃣ Open the .ipynb notebook in Google Colab
# 2️⃣ Upload the dataset (zip or extracted folders)
# 3️⃣ Run all cells sequentially to train the model
# 4️⃣ Use the model to predict gestures from test images

Predicted Gesture: 7

👤 Author

Thulasi Gaddam
SkillCraft Technology – Machine Learning Internship (Task 04)

