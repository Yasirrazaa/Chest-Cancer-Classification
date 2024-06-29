# Chest Cancer Classification Project

## Introduction

This project focuses on the classification of chest cancer using machine learning techniques. The goal is to accurately classify and predict the presence of cancer based on chest X-ray images. This involves the use of image processing and deep learning models to analyze and learn from a dataset of X-ray images, distinguishing between healthy and cancerous cases.

## Dataset

The dataset used in this project comprises chest X-ray images categorized into four main classes: 
The dataset can be found on [Kaggle](https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images).


Key characteristics of the dataset include:

- **Size**: The dataset contains thousands of labeled images.
- **Source**: Publicly available medical image repositories.
- **Format**: Images are stored in JPEG/PNG format.

## Technology Used

The project leverages several technologies and frameworks:

- **Python**: The primary programming language used for scripting and model development.
- **TensorFlow and Keras**: For building and training the deep learning models.
- **OpenCV**: For image processing tasks.
- **NumPy and Pandas**: For data manipulation and analysis.
- **Flask**: For creating a web application to demonstrate the model's capabilities.
- **Git**: For version control.
- **DVC**: For Data version control.
- **MLflow**: For experiment tracking.

## Project Structure

The project is organized into several key folders and files:

- **`/config`**: Contains configuration file for different stages.
- **`/research`**: Contains the notebooks used for experimentation.
- **`/src`**: Contains Python scripts for data preprocessing, model training, and evaluation.
- **`app.py`**: Includes the Flask web application files for deploying the model as a web service.
- **`requirements.txt`**: Lists all the Python libraries and their versions required to run the project.
- **`README.md`**: Provides an overview of the project, dataset, technologies used, and instructions for running the project.

## Running the Project Locally

To run this project on your local machine, follow these steps:

1. **Clone the Repository**

   Clone the project repository to your local machine using Git:

   ```bash
   git clone https://github.com/your-username/chest-cancer-classification.git
   cd chest-cancer-classification
   ```

2. **Set Up a Python Environment**

   It's recommended to create a virtual environment for the project:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**

   Install the required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Web Application**

   Navigate to the main directory and start the Flask application:

   ```bash
   python app.py
   ```

   This will start the web server, and you can access the web application by navigating to `http://127.0.0.1:8080/` in your web browser or you will see it in your terminal.

5. **Using the Application**

   - Upload a chest X-ray image through the web interface.
   - Submit the image for analysis.
   - The model will classify the image as Normal or Cancerous and display the result.

## Conclusion

This Chest Cancer Classification project demonstrates the power of deep learning in medical imaging. By leveraging advanced image processing and machine learning techniques, it offers a valuable tool for early detection and diagnosis of chest cancer, potentially saving lives through timely intervention.
