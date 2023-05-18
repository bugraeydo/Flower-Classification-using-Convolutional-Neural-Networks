# Flower-Classification-using-Convolutional-Neural-Networks

This repository contains code for a flower classification task using convolutional neural networks (CNNs). The goal is to build a model that can accurately classify images of flowers into five different categories: roses, daisies, dandelions, sunflowers, and tulips.

## Dataset

The flower dataset used in this project can be found at [flower_photos](https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz). It consists of a collection of flower images grouped into different categories. The dataset is preprocessed and prepared for training the CNN model.

## Requirements

To run the code in this repository, you need the following dependencies:

- Python (version 3.6 or higher)
- Jupyter Notebook
- NumPy
- OpenCV
- Matplotlib
- scikit-learn
- TensorFlow

You can install the required packages by running the following command:
pip install -r requirements.txt

## Usage

1. Clone the repository:

git clone https://github.com/your-username/flower-classification.git

2. Change into the project directory:

cd flower-classification

3. Open the Jupyter Notebook:

jupyter notebook

4. Run the notebook `flower_classification.ipynb` to train and evaluate the CNN model.

## Model Architecture

The CNN model used for flower classification consists of multiple convolutional layers, max-pooling layers, and dense layers. The architecture is designed to extract meaningful features from the flower images and classify them into the respective categories.

## Results

After training the model on the flower dataset, the performance of the model is evaluated on a separate testing set. The evaluation includes the calculation of loss and accuracy metrics. The results are displayed at the end of the notebook.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to use and modify the code according to your needs.

If you encounter any issues or have questions, please feel free to contact [your-email@example.com](mailto:your-email@example.com).

Happy coding!
