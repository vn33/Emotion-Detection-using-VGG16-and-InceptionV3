# Emotion Detection using VGG16 and InceptionV3

Welcome to the Emotion Detection project! This project leverages the power of deep learning models, VGG16 and InceptionV3, to detect emotions from images. Dive in to see how we preprocess data, develop models, and assess their performance.

## 📚 Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Development](#model-development)
- [Contributing](#contributing)

## Project Overview
Emotion detection is a vital task in the field of computer vision and has numerous applications in various domains such as human-computer interaction, security, and social media analysis. This project aims to build robust models using VGG16 and InceptionV3 architectures to classify emotions accurately.

## Installation
To get started with this project, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/vn33/Emotion-Detection-using-VGG16-and-InceptionV3.git
    cd emotion-detection
    ```

2. **Install the required libraries:**
    ```sh
    pip install -r requirements.txt
    ```

3. **Set up Kaggle API (if using Kaggle datasets):**
    - Ensure you have your Kaggle API key stored in `~/.kaggle/kaggle.json`.

## Usage
Follow these steps to use the notebook and train the models:

1. **Open the Jupyter Notebook:**
    ```sh
    jupyter notebook EmotionDetection.ipynb
    ```

2. **Run the cells step-by-step:**
    - **Setting up Kaggle Directory**
    - **Import Libraries**
    - **Dataset Analysis**
    - **Data Splitting into Training & Validation Sets**
    - **Data Augmentation & Preprocessing**
    - **Model Development**
    - **Model Training & Performance Assessment**

3. **Evaluate the model:**
    - The notebook contains sections for evaluating the performance of the custom model, VGG16, and InceptionV3 models.

## Dataset
The dataset used for this project consists of images categorized into various emotions. The dataset is split into training and validation sets, and includes augmentation techniques to enhance the model's robustness.

### Dataset Analysis
- **Accept specific image formats**
- **Categories Distribution**
- **Image Dimension Analysis**
- **Plot Images from Categories**

## Model Development
### Custom Model Architecture
- **Model Training**
- **Model Performance Assessment**

### VGG16 Model
- **Model Training leveraging pre-trained weights**
- **Model Performance Assessment**

### InceptionV3 Model
- **Model Training leveraging pre-trained weights**
- **Model Performance Assessment**

## Contributing
Contributions are welcome! If you have any improvements or new features to add, feel free to open a pull request or issue.


---

Happy coding! If you have any questions or feedback, please open an issue in the repository. Let's build amazing emotion detection models together!
