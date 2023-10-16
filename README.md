
# Instrument Image Classifier

This project implements a deep learning-based image classifier using the VGG16 architecture to classify images of musical instruments. The classifier is trained on a dataset containing various instrument categories and can predict the instrument in an uploaded image.

## Technologies Used

- **Python**: The core language used for coding the project.
- **TensorFlow and Keras**: Used for building and training the deep learning model.
- **OpenCV**: Utilized for image processing tasks.
- **Matplotlib**: Used for displaying images and visualizations.
- **Scikit-Learn**: Utilized for various machine learning utilities.
- **Tkinter**: Used for building the graphical user interface (GUI) for image uploading and prediction display.
- **NumPy**: Used for numerical computations.
- **PIL (Pillow)**: Utilized for handling image files.
- **Joblib**: Used for saving and loading machine learning models.

## Project Structure

- **`dataset/`**: Contains the training and testing images categorized by instrument types.
- **`train.py`**: Script to train the instrument classifier model.
- **`predict.py`**: Script for predicting instrument categories from individual images.
- **`gui.py`**: Contains the Tkinter-based GUI for uploading and classifying images.
- **`cnn_instruments_classifier.h5`**: Pretrained instrument classifier model.
- **`requirements.txt`**: File containing the necessary dependencies to run the project.

## Usage

1. **Training the Model**:
    - Run `train.py` to train the classifier on the provided dataset.
    - The trained model will be saved as `cnn_instruments_classifier.h5`.

2. **Predicting with Individual Images**:
    - Run `predict.py` and provide the path to the image you want to classify.
    - The script will output the predicted instrument category.

3. **Using the GUI**:
    - Run `gui.py` to open the Tkinter-based interface.
    - Click the "Upload Image" button to select an image for classification.
    - The predicted instrument category will be displayed in the GUI.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Instrument-Image-Classifier.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Instrument-Image-Classifier
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the GUI application:
   ```bash
   python gui.py
   ```

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or create a pull request.

## Outcomes:

**Layout:**

![Screenshot (90)](https://github.com/Bhudil/Instruments_Classifier/assets/99169324/ddfe9bf5-7548-4a49-a0f1-66bd5c01d57c)


**Use-case 1:**

![Screenshot (86)](https://github.com/Bhudil/Instruments_Classifier/assets/99169324/79c2bd35-9411-44a4-b64d-2735dc2521e8)


**Use-case 2:**

![Screenshot (87)](https://github.com/Bhudil/Instruments_Classifier/assets/99169324/2bd7a5c3-4b28-4a87-a9bd-75fe32941f0e)


**Use-case 3:**

![Screenshot (88)](https://github.com/Bhudil/Instruments_Classifier/assets/99169324/814cb9a6-2f1a-46c9-aa73-d8800c1b12c6)


**Use-case 4:**

![Screenshot (89)](https://github.com/Bhudil/Instruments_Classifier/assets/99169324/c2164bfe-5ba6-4db6-a4b6-44521066c6e9)


---

Feel free to customize the README according to your project's specifics. This template covers the essential information required for users and contributors to understand your project and how to use it.
