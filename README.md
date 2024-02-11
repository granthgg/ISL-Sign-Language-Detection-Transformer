# ISL SIGN LANGUAGE DETECTION TRANSFORMER

## Overview
The "ISL Sign Language Detection Transformer" project leverages advanced deep learning techniques, specifically Transformer models, to detect and translate Indian Sign Language (ISL) into text. This project aims to make communication more accessible for the deaf and hard-of-hearing community by using technology to bridge the gap between sign language and spoken/written languages.

## Key Features
- **Real-time ISL Detection**: Utilizes a Transformer model for real-time detection and translation of ISL signs.
- **Comprehensive Dataset**: Includes a dataset with signs representing the ISL alphabet and common phrases, facilitating a wide range of communication needs.
- **Interactive Application**: Features an interactive Jupyter Notebook (`Application.ipynb`) for easy demonstration and testing of the model's capabilities.
- **In-depth Training Process**: Detailed training notebooks (`Train_Transformer.ipynb`) explain the model training process, including data collection, preprocessing, and model architecture details.

## Technologies Used
- **TensorFlow & Keras**: For building and training the Transformer model.
- **OpenCV**: For real-time video processing and sign language detection.
- **MediaPipe**: For efficient hand and pose tracking within the video feed.
- **Jupyter Notebook**: For interactive code execution, documentation, and testing.

## Project Structure
- `MP_Data/`: Directory containing the preprocessed ISL dataset, organized by signs (A-Z, common phrases).
- `Application.ipynb`: Notebook for deploying the trained model for ISL sign detection.
- `Data Collection.ipynb`: Notebook for data collection and preprocessing.
- `Testing_Transformer_Train.ipynb`: Notebook for testing the Transformer model training process.
- `Train_Transformer.ipynb`: Notebook detailing the training process of the Transformer model on the ISL dataset.

## Getting Started
1. **Clone the Repository**
2. **Set Up Your Environment**
- Ensure you have Python and Jupyter Notebook or JupyterLab installed.
- Install required dependencies (listed in a hypothetical `requirements.txt` or directly in the notebooks).

3. **Explore the Notebooks**
- Start with `Data Collection.ipynb` for understanding data collection and preprocessing.
- Proceed with `Train_Transformer.ipynb` to train the model.
- Use `Application.ipynb` to deploy the model for ISL sign detection.

## Contributing
We welcome contributions to improve the project. Please fork the repository, make your changes, and submit a pull request.

