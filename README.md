
# Emojify: Turn Facial Expressions into Emojis

**Note:** This project is under development and may have recognition errors.

## Project Highlights

1. Selected emojis for facial expressions.
2. Captured and stored 250 images for each facial expression, focusing on eyebrows, eyes, nose, and mouth.
3. Trained a CNN using these images.
4. Currently, 11 facial expressions are recognized.

## Outcome

View the project [here](https://youtu.be/izUO2rl0Ur8).

## Requirements

- Python 3.x
- TensorFlow 1.5
- Keras
- OpenCV 3.4
- h5py
- Basic knowledge of neural networks and machine learning
- dlib
- Good CPU (preferably with GPU)
- Patience
- Tensorboard for visualization

## Facial Expressions Recognized

0 - Neutral<br>
1 - Smile/Happy<br>
2 - Sad<br>
3 - Wink<br>
4 - Kiss<br>
5 - Surprised<br>
6 - Angry<br>
7 - Monkey face<br>
8 - Wink with tongue out<br>
9 - Scared/Terrified<br>
10 - Disgusted<br>

## Usage

This project is trained using a single face (the creator's) and may not detect other expressions accurately. Here's how you can use it:

1. Create your facial expression dataset using `create_dataset_webcam.py`.
2. Optionally, retrain the model with your dataset using `retrain_cnn_keras.py`.
3. Check the model's accuracy against the original dataset using `compute_accuracy.py`.
4. If you're satisfied with the accuracy, start `emojify.py` to turn your facial expressions into emojis.

## Contribution

You can contribute to the dataset by making a pull request. Please move your dataset contents from `new_dataset/` to `dataset/` before creating a pull request. Feel free to optimize the code as well.

## Citation

Saha, D. (2018, May 9). Emojify (Version 1). figshare. https://doi.org/10.6084/m9.figshare.6241934.v1.

---
