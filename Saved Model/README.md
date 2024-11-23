# Model of Stock Pred

This repository contains the saved models and necessary files for a stock prediction application. The application utilizes machine learning techniques to forecast stock prices based on historical data.

## Files Included
**model.tflite**: This is the TensorFlow Lite model file, optimized for mobile and edge devices. It allows for efficient inference on devices with limited resources.
**model**: This file represents the main model used for predictions. It contains the architecture and weights of the trained model.
**model_terbaik.keras**: This file contains the best-performing model saved in Keras format. It can be loaded directly for further training or inference.
**Record hyperparameter tuning**: This file includes records of the hyperparameter tuning process, detailing the parameters tested and their corresponding performance metrics.
**skala_X**: This file contains the scaling parameters for the input features, ensuring that the model receives data in the correct format.
**skala_X.pkl**: A serialized version of the scaling parameters for easy loading and application during inference.
**skala_y**: This file contains the scaling parameters for the target variable, which is essential for transforming predictions back to their original scale.
**skala_Y.pkl**: A serialized version of the target variable scaling parameters, facilitating the inverse transformation of predictions.
**tfjs_model**: This folder contains the model files converted for use with TensorFlow.js, allowing for deployment in web applications.
**Training Results of Combined Model**: Shows images of the results of training

## Usage
**Loading the Model**: Use the appropriate library (TensorFlow, Keras, etc.) to load the model files for predictions.
**Data Preprocessing**: Ensure that the input data is preprocessed using the scaling parameters provided in Skala_X and Skala_X.pkl.
**Making Predictions**: After loading the model and preprocessing the data, you can make predictions on stock prices.
**Inverse Scaling**: Use skala_y and skala_Y.pkl to transform the predicted values back to their original scale for interpretation.

## Installation
To run this application, ensure you have the following libraries installed:
- **TensorFlow**
- **Keras**
- **NumPy**
- **Pandas**

You can install the required libraries using pip:
```sh
   pip install tensorflow keras numpy pandas
   ```


