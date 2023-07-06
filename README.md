# Fertilizer-Prediction-ML-Model
Machine Learning Model to Train and Prediction Fertilizers from Given Data Using Logistic Regression.
This repository contains the implementation of a machine learning model for fertilizer prediction. The model aims to predict the most suitable fertilizer for a given set of soil and crop parameters. The implementation includes data preprocessing, model training, and evaluation.

## Dataset

The dataset used for training and testing the model consists of soil and crop parameters along with the corresponding fertilizer recommendations. The dataset is provided in the `data.csv` file. It contains the following columns:

- `Temperature`: Temperature of the soil in degrees Celsius.
- `Humidity`: Humidity of the soil in percentage.
- `pH`: pH value of the soil.
- `Nitrogen`: Nitrogen content in the soil in parts per million (ppm).
- `Phosphorous`: Phosphorous content in the soil in ppm.
- `Potassium`: Potassium content in the soil in ppm.
- `Fertilizer`: Recommended fertilizer for the given set of parameters.

## Model Training

The model is trained using a supervised learning approach. The dataset is split into training and testing sets, with 80% of the data used for training and 20% for testing. The training data is used to train the model to learn the patterns and relationships between the input parameters and the recommended fertilizer. The model is evaluated using the testing data to assess its performance and accuracy.

## Dependencies

- Python 3.x
- Pandas
- NumPy
- Scikit-learn

## Usage

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the `train_model.py` script to train the model.
4. Once the model is trained, you can use the `predict_fertilizer.py` script to make predictions for new soil and crop parameters.

## Contributing

Contributions to this project are welcome. If you find any issues or have any suggestions for improvement, please feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

## Acknowledgements

This project is inspired by the need for accurate fertilizer recommendations in agriculture. Special thanks to the authors and contributors of relevant research papers and online resources.

