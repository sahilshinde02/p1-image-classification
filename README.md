# Imsage: ML Model for Image Classification
[Live Demo](https://imsage.streamlit.app/)
**Imsage** is an image classification web application built using Streamlit and TensorFlow. It integrates two powerful machine learning models: MobileNetV2 (trained on ImageNet) and a custom CIFAR-10 model. This app allows users to upload images and get predictions along with confidence scores from either of the two models. With an intuitive navigation interface, users can seamlessly switch between models and receive real-time predictions. The app also provides an option to download prediction results in CSV format, making it a useful tool for both learning and practical applications in image classification.

## Key Features

- **Dual Model Support**:
  - **MobileNetV2 (ImageNet)**: Classifies images into 1,000 categories from the ImageNet dataset, including everyday objects, animals, and vehicles.
  - **Custom CIFAR-10 Model**: Specializes in classifying images into one of ten categories such as airplanes, automobiles, birds, cats, and more.

- **User-Friendly Interface**:
  - **Navigation Bar**: Easily switch between MobileNetV2 and CIFAR-10 models with a sleek sidebar menu.
  - **Real-Time Predictions**: Upload an image to receive instant predictions along with confidence scores.

- **Educational and Practical Applications**:
  - Ideal for learning about deep learning models and their performance.
  - Useful for practical applications where image classification is required.

- **Batch Image Upload**: Supports uploading multiple images at once for batch processing and classification.
  
- **Top 3 Predictions**: Displays the top 3 predicted classes with confidence scores to provide a more comprehensive output.
  
- **CSV Download**: Users can download their prediction results in CSV format for further analysis or record-keeping.

- **Mobile Compatibility**: A fully responsive design that works smoothly on both desktop and mobile devices.

- **Image Preprocessing**: Automatically resizes and preprocesses images for model compatibility before making predictions.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- A web browser (Chrome, Firefox, etc.)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Keshabkjha/Imsage.git
   cd Imsage

2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
4. **Start the Streamlit app**:
    ```bash
    streamlit run app.py
5. **Open the app**: 
    The app will open in your default web browser. If not, navigate to http://localhost:8501
  Check out the live demo [here](https://imsage.streamlit.app/).
### Contributing
  Feel free to fork the repository, open issues, or submit pull requests to contribute to the project.

### Acknowledgements
  - **Streamlit:** For providing an easy-to-use framework to create web apps.
  - **TensorFlow:** For the powerful pre-trained deep learning models.
