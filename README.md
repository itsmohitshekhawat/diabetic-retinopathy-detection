# VISIONAID

## Overview

VISIONAID is an automated system designed for the early detection of diabetic retinopathy from retinal images. Leveraging Convolutional Neural Networks (CNNs), the system categorizes images into different stages of diabetic retinopathy, enabling prompt diagnosis and intervention. This repository encompasses the implementation of the CNN model, dataset processing scripts, and a user-friendly web application for seamless interaction.

## Key Features

- **CNN Model**: Includes the implementation of a CNN model trained on retinal images to classify diabetic retinopathy stages.
- **Dataset Processing**: Scripts for preprocessing and augmenting retinal image datasets to prepare them for training the CNN model.
- **Web Application**: A user-friendly web interface for uploading retinal images and obtaining predictions regarding diabetic retinopathy stages.

## Model Performance

The CNN model was independently trained and evaluated on two datasets:

- **EyePACS Dataset**: Achieved an accuracy of 80%.
- **APTOS Dataset**: Achieved an impressive accuracy of 95%.

## Repository Structure

The repository is structured as follows:

- **models/**: Contains directories for different versions of the CNN model trained on the EyePACS and APTOS datasets.
- **public/**: Includes static assets such as images and HTML files for the web application.
- **src/**: Contains the source code for the web application, including JavaScript and CSS files.
- **requirements.txt**: Lists the Python dependencies required for running the project.
- **README.md**: Provides an overview of the project, its features, and instructions for usage.

## Installation

To set up the project locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install the required Python dependencies using pip:
   `pip install -r requirements.txt`
4. Ensure Node.js is installed on your machine.
5. Install the required Node modules for the web application:
   npm install

## Usage

After installation, you can run the web application locally:

1. Navigate to the project directory.
2. Start the FastAPI server using Uvicorn:
   `uvicorn main:app --reload`

3. Access the web application in your browser at `http://localhost:8000`.

## Contributing

Contributions to VISIONAID are welcome! If you find any issues or have suggestions for improvements, please open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Special thanks to the creators and maintainers of the EyePACS and APTOS datasets for their valuable contributions to diabetic retinopathy research.
- This project was developed as part of [Your Organization]'s efforts to improve healthcare accessibility and diagnosis using machine learning technologies.
