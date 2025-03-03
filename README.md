# Text Classification Using TensorFlow

This is a machine learning project for classifying text data into different categories. The model uses TensorFlow to preprocess the data, train a neural network, and evaluate its performance on the test set.

## Dataset

The dataset consists of labeled text samples across multiple categories. Preprocessing steps include:

- Tokenizing and encoding the text data
- Padding sequences to ensure uniform input length
- Splitting the dataset into training, validation, and test sets

## Model

The model architecture includes the following layers:

- **Embedding Layer**: Converts word indices into dense vectors
- **LSTM Layer**: Captures sequential dependencies in the text
- **Dense Layer**: Fully connected layer with ReLU activation
- **Output Layer**: Activation depends on classification type (softmax for multiclass, sigmoid for binary)

The model was trained using the Adam optimizer and categorical cross-entropy loss for multiclass classification.

## Results

The model achieved the following performance metrics on the test set:

- **Accuracy**: ~90%
- **Precision and Recall**: Detailed per-category metrics are visualized in the notebook
- **Confusion Matrix**: Highlights classification performance across categories

## Contribution

Contributions are welcome! Feel free to fork the repository, make improvements, and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

