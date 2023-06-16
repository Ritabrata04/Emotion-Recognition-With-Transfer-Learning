# Emotion Recognition With Transfer Learning

This project leverages the power of Deep Learning, particularly Convolutional Neural Networks (CNN), for Emotion Recognition tasks. The primary toolset includes Tensorflow, a popular open-source library for numerical computation, and the VGG16 model, a pre-trained model renowned for its effectiveness in image classification tasks.

The foundation of this project lies in the concept of Transfer Learning, which allows us to use the pre-trained weights of a model (VGG16 in this case), trained on a different but large and general dataset, and apply these learned feature representations to our specific task — Emotion Recognition.

The dataset used in this project is FER2013, a widely-used dataset in the field of Emotion Recognition that contains grayscale facial images labeled into seven different emotions: Anger, Disgust, Fear, Happy, Sad, Surprise, and Neutral.

Please note that the project is still in progress. The code may contain some errors that are currently being worked on. Watch this space for future updates.

## Dataset 

The dataset used for training, validation and testing is FER2013. It consists of 48x48 pixel grayscale images of faces, divided into seven categories (emotions): Anger, Disgust, Fear, Happy, Sad, Surprise, and Neutral. 

## Setup and Installation

To get started with the project, you will need Python 3.7+ and the following Python libraries installed:

- Tensorflow
- Keras
- OpenCV
- Numpy
- Matplotlib

You can install these packages using pip:

```bash
pip install tensorflow keras opencv-python numpy matplotlib
```

To clone the repository and run the scripts, use the following commands:

```bash
git clone https://github.com/username/project.git
cd project
python main.py
```

Please replace 'username' and 'project' with the actual GitHub username and project name.

## Project Structure

The project is structured into various Python scripts with each script handling a specific aspect of the model:

- `preprocessing.py` : For preprocessing and cleaning the FER2013 dataset.
- `model.py` : Contains the main architecture of the model leveraging VGG16.
- `train.py` : For training the model.
- `predict.py` : To predict emotions on new inputs using the trained model.

## Updates

As mentioned before, this project is a work in progress. Updates will be pushed to the repository as the project progresses, so stay tuned!

## Contribution

Contributions, issues, and feature requests are welcome. Feel free to check issues page if you want to contribute.

## License

[MIT](https://choosealicense.com/licenses/mit/)
