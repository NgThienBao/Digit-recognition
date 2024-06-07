# Digit Recognition

## Project Overview
The goal of this project is to develop neural network models that can accurately classify handwritten digits from the MNIST dataset. The MNIST dataset is a well-known benchmark in the field of machine learning and computer vision.

### Models Included:
- EfficientNetV2
- Inception_v3
- Resnet_v2
- MNISTRecog
- Multilayer Perceptron (MLP)

## How to Run the Code

### 1. Install Kaggle API
Ensure you have Python installed. If not, download and install Python from [python.org](https://www.python.org/).
Install the Kaggle API by running the following command in your terminal:

pip install kaggle

### 2. Obtain Kaggle API Credentials
Go to your Kaggle account settings: Kaggle Account.
Scroll down to the "API" section and click "Create New API Token". This will download a kaggle.json file containing your API credentials.
### 3. Set Up Kaggle API Credentials
Move the kaggle.json file to a secure location. A common practice is to place it in the ~/.kaggle directory. For example:

mkdir ~/.kaggle
mv /path/to/kaggle.json ~/.kaggle/
chmod 600 ~/.kaggle/kaggle.json
### 4. Download the Dataset
If you are using VS Code, open a terminal.
Use the Kaggle API to download the dataset by running:

kaggle competitions download -c digit-recognizer
This command will download the dataset to your current working directory.

### 5. Unzip the Dataset
Once the dataset is downloaded, unzip it using the following command:

unzip digit-recognizer.zip -d digit-recognizer
This will extract the contents to a folder named digit-recognizer.

### 6. Run the Jupyter Notebook
Open the provided Jupyter Notebook file (Test.ipynb) in VS Code or Jupyter Lab. 

pip install numpy pandas keras matplotlib
### 7. Train and Evaluate the Models
Follow the steps in the notebook to preprocess the data, build the models, train them, and evaluate their performance.
By RunAll button to see the result


