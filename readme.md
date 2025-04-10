# Plant Leaf Disease Detection

This project is a **Plant Leaf Disease Detection System** that leverages machine learning to identify diseases in plant leaves. The user interface is built using **Streamlit**, making it interactive and easy to use.

---

## Features
- Detect plant leaf diseases using machine learning models.
- Simple and intuitive UI built with Streamlit.
- Step-by-step instructions for setup and usage.

---

## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Project Structure](#project-structure)
5. [Model Training](#model-training)
6. [Team Members](#team-members)

---

## Prerequisites
Before running the project, ensure you have the following installed:
- Python 3.7 or higher
- pip (Python package manager)
- Basic knowledge of Python (optional but helpful)

---

## Installation
Follow these steps to set up the project on your local machine:

1. **Clone the Repository**
    ```bash
    git clone https://github.com/your-repo/plant-leaf-disease-detection.git
    cd plant-leaf-disease-detection
    ```

2. **Install Dependencies**
    Install the required Python libraries using pip:
    ```bash
    pip install -r requirements.txt
    ```

3. **Download the Dataset**
    - Download the dataset from [this link](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset).
    - Place the dataset in the `data/` directory.
    - Ensure the dataset is structured properly (e.g., separate folders for each class of disease).

---

## Usage
1. **Run the Streamlit App**
    Start the Streamlit application by running:
    ```bash
    streamlit run app.py
    ```

2. **Upload an Image**
    - Use the UI to upload an image of a plant leaf.
    - The model will analyze the image and display the predicted disease.

3. **View Results**
    - The app will show the disease name and confidence score.

---

## Project Structure
```
plant-leaf-disease-detection/
│
├── app.py                 # Main Streamlit application
├── model/                 # Directory for ML models
│   ├── train_model.py     # Script for training the model
│   └── saved_model.pkl    # Pre-trained model file
├── data/                  # Directory for datasets
├── utils/                 # Helper functions
│   └── preprocess.py      # Image preprocessing utilities
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

---

## Model Training
If you want to train the model yourself:
1. Place your dataset in the `data/` directory.
2. Run the training script:
    ```bash
    python model/train_model.py
    ```
3. The trained model will be saved in the `model/` directory.

---

## Team Members
- **Bipin Kumar Chaudhary** (21053451)  
- **Jay Prakash Giri** (21053460)  
- **Mahi Kumari** (21053345)  
- **Sudhir Jaiswal** (21053381)