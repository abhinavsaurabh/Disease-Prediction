
# Disease Prediction Using Machine Learning

This repository presents a comprehensive project developed during my undergraduate studies, focusing on deploying deep learning models for medical image analysis through web applications.

## Project Overview

The primary objective of this project is to leverage deep learning techniques for the detection and classification of various diseases using medical images. The application encompasses the following features:

- **Disease Detection**: Identifies and categorizes six diseases:
  - **Malaria**: Detection using cell images.
  - **Brain Tumor**: Detection using MRI scans.
  - **Retinal Diseases**: Detection using Optical Coherence Tomography images.
  - **Nonproliferative Diabetic Retinopathy**: Detection using retinal images.

- **Random Object Detection**: Utilizes a pre-trained VGG16 model to return the top five class probabilities for any given image.

## Model Performance

The table below summarizes the accuracy achieved by each disease detection model:

| Disease                             | Model Architecture | Accuracy |
|-------------------------------------|--------------------|----------|
| Malaria                             | Custom CNN         | 95.00%   |
| Brain Tumor                         | Custom CNN         | 92.50%   |
| Retinal Diseases                    | Custom CNN         | 93.00%   |
| Nonproliferative Diabetic Retinopathy | Custom CNN       | 91.50%   |

*Note: The accuracies are based on validation datasets and may vary with different datasets.*

## Code Structure

The repository is organized as follows:

- **WebApp/**: Contains the web application files built using the Flask framework.
  - **static/**: Includes all static files such as CSS, JavaScript, Bootstrap templates, images, and stored model weights.
  - **templates/**: Houses all HTML files used across the project. Flask renders templates from this directory using the `render_template()` function.
  - **core_app.py**: The main backend file where all Flask and Python logic resides. Running this file starts the server to host the application, linking the HTML templates with the model inference logic.
  - **index.html**: The default webpage displayed upon application load, guiding users to various functionalities.

- **Final Paper.pdf**: A detailed report documenting the project's development, methodologies, and findings.

- **LICENSE**: Specifies the licensing information for the project.

## Technical Implementation

- **Model Training**: Deep learning models were trained using Convolutional Neural Networks (CNNs) for each disease category. Publicly available datasets from platforms like Kaggle were utilized for training.

- **Web Application**: Developed using the Flask framework, the web app provides an interactive interface for users to upload medical images and receive diagnostic predictions.

- **Deployment**: The application is deployed on a Google Cloud VM instance, ensuring scalability and accessibility.

## Usage

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/abhinavsaurabh/Disease-Prediction.git
   ```

2. **Navigate to the WebApp Directory**:

   ```bash
   cd Disease-Prediction/WebApp
   ```

3. **Install Dependencies**:

   Ensure you have Python installed. Then, install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:

   Start the Flask server:

   ```bash
   python core_app.py
   ```

5. **Access the Application**:

   Open a web browser and navigate to `http://localhost:5000` to interact with the application.

## Future Enhancements

Potential improvements for this project include:

- **Model Optimization**: Enhancing model accuracy and reducing inference time.
- **Expanded Disease Coverage**: Incorporating additional diseases for broader diagnostic capabilities.
- **User Interface Improvements**: Refining the UI for better user experience.

## Acknowledgments

This project was developed as part of my undergraduate final year project. I extend my gratitude to my mentors and peers for their invaluable support and guidance throughout this endeavor.

---
