
# Water Purification Level Detection Through Microorganism Using Deep Learning

## Project Overview

This project aims to detect the purity of water by analyzing the presence of pathogenic microorganisms in microscopic images. By leveraging deep learning techniques on the Environmental Microorganism Dataset (EMDS), the model can classify water samples as either pure or impure based on the detected microorganisms.

## Features

- **Image Classification**: Classifies images as either containing pathogenic or non-pathogenic microorganisms.
- **Deep Learning**: Utilizes advanced deep learning models for accurate classification.
- **Dataset**: Uses the EMDS dataset for training and evaluation.
- **Purity Detection**: Automatically determines if water is pure or impure based on the classification results.

## Dataset

The project uses the Environmental Microorganism Dataset (EMDS), which contains images of various microorganisms. The dataset is divided into two categories:

1. **Pathogenic**: Microorganisms that are harmful and indicate that the water is impure.
2. **Non-pathogenic**: Harmless microorganisms, indicating that the water is pure.

## Model Architecture

The model is built using a convolutional neural network (CNN) with the following components:

- **Input Layer**: Takes the microscopic images as input.
- **Convolutional Layers**: Extracts features from the images.
- **Pooling Layers**: Reduces the dimensionality of the feature maps.
- **Fully Connected Layers**: Maps the extracted features to the output classes.
- **Output Layer**: Classifies the image as either pathogenic or non-pathogenic.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Water-Purification-Level-Detection.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Training the Model**: To train the model, run the following command:
    ```bash
    python train.py --dataset path_to_dataset
    ```
2. **Testing the Model**: To test the model on a new set of images, use:
    ```bash
    python test.py --image path_to_image
    ```
3. **Detecting Water Purity**: Run the model on an image to determine if the water is pure or impure:
    ```bash
    python detect_purity.py --image path_to_image
    ```

## Results

- The model achieves high accuracy in distinguishing between pathogenic and non-pathogenic microorganisms.
- Detailed evaluation metrics and visualizations of the results are provided in the `results` directory.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements

- The project is based on the EMDS dataset, which is openly available for research purposes.

---

You can customize the content based on the specifics of your project and the details in your code. Let me know if you'd like to add or modify any sections!
# Model Evaluation using Streamlit
- https://environmental-microorganism-detection.streamlit.app/
