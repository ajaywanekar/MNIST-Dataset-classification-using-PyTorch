# Number Recognition using PyTorch 

This project demonstrates the implementation of the LeNet-5 convolutional neural network for handwritten digit recognition using the MNIST dataset.

## Project Structure

The project is organized as follows:

- `main.py`: Contains the main script to train and evaluate the LeNet-5 model.
- `model.py`: Defines the LeNet-5 model architecture.
- `utils.py`: Provides utility functions for data loading, preprocessing, and evaluation.
- `requirements.txt`: Lists the required dependencies for running the project.

## Usage

1. Prepare the dataset:

- Download the MNIST dataset and place it in the appropriate directory.
- Ensure the dataset is properly split into training and validation sets.

2. Train the model:


- Adjust the `data_path` argument according to the location of your dataset.
- Optionally, specify other training parameters such as learning rate, batch size, etc.

3. Evaluate the model:


- Adjust the `data_path` argument according to the location of your dataset.

4. Predict using the trained model:

- Modify the `inference()` function in `utils.py` to accept and process the input image.
- Use the modified function to make predictions on new images.

## Results

- For a given input image, the model predicted the digit as 8 with a probability of 99%.
predicted: 8, prob: 99.9998927116394 %


## Acknowledgements

- The MNIST dataset is used for training and evaluation.




## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ajay-wanekar-245a50230/)


[![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white
)](https://github.com/ajaywanekar)
