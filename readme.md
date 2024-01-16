# Detecting Trigger Words in Emergency Situations

This project develops a deep learning model to detect trigger words in emergency situations, inspired by the "Trigger Word Detection" exercise from the [Deep Learning Specialization on Coursera](https://www.coursera.org/specializations/deep-learning). This project focuses on audio processing and model training using deep learning techniques. It's designed to work with audio data, perform preprocessing, and train a model to recognize specific audio patterns or commands. 

## Description

In this project, a deep learning model that can detect trigger words in emergency situations is being developed. Trigger words are critical phrases or keywords that, when identified, can indicate that an emergency or crisis has occurred. For example help, please, fire etc. The project will attempt to detect whether these trigger words are present in various audio sources such as emergency calls, radio communications or other relevant audio data.

## Getting Started

### Dependencies

- Python 3.x
- TensorFlow
- Pydub
- Numpy
- Matplotlib
- SciPy
- IPython (for Jupyter Notebooks)
- Google Colab (optional for cloud-based execution)

### Installing

1. Clone the repository or download the provided Jupyter Notebook.
2. If using Google Colab:
   - Mount your Google Drive to the Colab notebook using:
     ```python
     from google.colab import drive
     drive.mount('/content/drive')
     ```
   - Set the folder name where the notebook and data are stored.

### Pre-trained Data

- **Train Set(X, Y)**: 
  - [ X, Y](https://drive.google.com/drive/folders/17b9RHVcXZRsDzC5jzrrUP3BIEqDm5Dex?usp=sharing)

- **Development Set (X_dev, Y_dev)**:
  - [X_dev, Y_dev](https://drive.google.com/drive/folders/1viXYi06NHXtHehskwQv96GvzC4wuvleg?usp=sharing)

- **Test Set (X_test, Y_test)**:
  - [X_test, Y_test](https://drive.google.com/drive/folders/1GtMtbYLMhNlxl9vc6waweW5v7Up6-uI4?usp=sharing)


### Executing program

1. Run the Jupyter Notebook cell by cell.
2. Make sure to set the correct paths for data and model files.
3. Execute the audio processing functions, followed by the model training and evaluation cells.

## Help

If you encounter issues related to audio file formats or dependencies, ensure all libraries are correctly installed and that the audio files are in the correct format (e.g., WAV).

## Authors

Emirberk Almacı
Furkan Öztürk
