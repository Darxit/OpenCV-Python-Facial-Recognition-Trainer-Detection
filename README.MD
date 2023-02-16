# facial-training-and-recognition

This is a simple python code for facial training and recognition using OpenCV.


### Software Requirements

- Numpy
- cv2
- Image from PIL

### Hardware Requirements
- Computer with good Camera.

## Usage

- Clone the Repository or Download the zip and extract.
- Install all the Requirements by running,
```pip install -r requirements.txt```
- First run the capturer.py program to capture the samples of face. The program will ask for the person's name/user, and the sample size (the amount of photos you want to be taken).
 - Next we need to run the trainer. To do so, we run ```python faces_train.py```
 Doing so produces a trained model "trainer.yml" and a pickle file containing the id of all the captured people.
 - After training, we can finally Run the Recognition Program. This makes use of the trained model and predicts the person. To start prediction we run, ```python face.py```

