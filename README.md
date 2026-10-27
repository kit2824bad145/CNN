# Cat or Dog Image Classification Using a Pretrained CNN

## Project Overview

This project uses a pretrained Convolutional Neural Network (CNN), MobileNetV2, to predict whether an uploaded image contains a cat or a dog. The model uses pretrained ImageNet weights and does not require training a new model.

## Objectives

- Load a pretrained CNN model.
- Upload a cat or dog image using Google Colab.
- Resize and preprocess the image.
- Predict the most likely image classes.
- Display the top five predictions and their scores.
- Show the uploaded image with its predicted classification.

## Technologies Used

- **Python** – Programming language.
- **TensorFlow/Keras** – Loads MobileNetV2 and performs prediction.
- **NumPy** – Processes image data.
- **Matplotlib** – Displays the image and prediction.
- **Google Colab** – Runs the program online.

## Model Details

- **Model:** MobileNetV2
- **Pretrained dataset:** ImageNet
- **Input image size:** 224 × 224 pixels
- **Output:** Top five predicted ImageNet classes
- **Classification:** Cat, dog, or not clearly a cat or dog.

## How the Program Works

1. Import the required libraries.
2. Load MobileNetV2 with pretrained ImageNet weights.
3. Upload an image through Google Colab.
4. Resize the image to 224 × 224 pixels.
5. Convert the image into an array.
6. Apply the required preprocessing.
7. Predict the image class using the CNN model.
8. Display the top five predictions and their scores.
9. Determine the final classification using the top predicted label.
10. Display the uploaded image with the prediction.

## How to Run in Google Colab

1. Open [Google Colab](https://colab.research.google.com/).
2. Create a new notebook.
3. Paste the complete Python program into a code cell.
4. Run the cell and wait for the model to load.
5. Upload a cat or dog image when prompted.
6. View the prediction results and displayed image.

**Note:** An internet connection is required to download the pretrained model weights the first time if they are not already available.

## Expected Output

The program displays:

- Model loading status.
- Top five predicted image labels and scores.
- The uploaded image with the final classification.
- The final predicted class and its score.

The results depend on the uploaded image and may vary in accuracy.

## Important Notes

- This program uses a pretrained CNN; it does not train a new CNN.
- The `cats_and_dogs_filtered.zip` dataset is not required.
- A single image is sufficient for prediction but not for training a custom classifier.
- The final classification is based on the top ImageNet prediction, so incorrect predictions are possible.

## Conclusion

This project demonstrates image classification using a pretrained CNN with TensorFlow and Keras. It allows users to upload an image, view the top predictions, and obtain a predicted classification without downloading a separate cat-and-dog dataset.


