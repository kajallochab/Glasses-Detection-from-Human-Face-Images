# Glass Detection on Human Faces using TensorFlow/Keras

This repository contains code for a deep learning model built with TensorFlow and Keras for detecting glasses on human faces in images.

## Overview

The project is structured into several sections:

1. **Data Cleaning**: The dataset is prepared, including converting images from PNG to JPG format and examining the dataset for quality issues.

2. **Data Processing**: The dataset is split into training, validation, and test sets. Data augmentation techniques are applied to increase the dataset size and improve model generalization.

3. **Preparing Base Model**: Transfer learning is used with the MobileNetV2 architecture as the base model. The base model is modified by adding custom classification layers.

4. **Training the Model**: The model is compiled and trained on the dataset. Both training and validation accuracies and losses are monitored.

5. **Fine-Tuning**: After initial training, the top layers of the base model are unfrozen, and the entire model is fine-tuned to improve performance further.

6. **Prediction**: The trained model makes predictions on unseen test data. Sample predictions are visualized along with the corresponding images.

7. **Convert to TFLite**: The trained model is converted to TensorFlow Lite format for deployment on resource-constrained devices.

8. **Debugging**: A debugging code is included to verify the functionality of the TensorFlow Lite model.

## Usage

To use this code for glass detection on human faces, follow these steps:

1. Ensure all necessary dependencies are installed. This includes TensorFlow, Keras, Matplotlib, NumPy, and other libraries used in the code.

2. Prepare your dataset or use the provided dataset. Ensure that the dataset is structured correctly with appropriate class labels.

3. Modify the paths and parameters in the code to fit your dataset and requirements.

4. Run each code section sequentially, monitoring outputs and visualizations for insights.

5. Evaluate the model's performance on test data and fine-tune parameters as needed.

6. Convert the trained model to TensorFlow Lite format if deployment on mobile or edge devices is required.

7. Use the TensorFlow Lite model for inference on target devices.

## Acknowledgments

This project is adapted from the TensorFlow tutorials on transfer learning and fine-tuning.

## Author

[Kajal Lochab](https://github.com/kajallochab)
[Lakshin Pathak](https://github.com/LakshinPathak)

## License

This project is licensed under the MIT License.
