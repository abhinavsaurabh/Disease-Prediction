
# Disease Prediction Using Machine Learning

This repository contains the code and documentation for my undergraduate final project, which focuses on developing a machine learning-based web application for disease prediction.

## Project Overview

The objective of this project is to leverage machine learning algorithms to predict diseases based on input data. The application is designed to assist in early diagnosis by analyzing user-provided information and predicting potential health conditions.

## Features

- **User-Friendly Interface**: The web application provides an intuitive interface for users to input their data.
- **Machine Learning Models**: Implemented models for disease prediction.
- **Real-Time Predictions**: The system offers instant predictions based on user input.

## Code Structure

The repository is organized as follows:

- **WebApp/**: Contains the Flask web application code.
  - **static/**: Includes static assets like CSS and JavaScript files.
  - **templates/**: Houses HTML templates for the web pages.
  - **app.py**: The main Flask application script that runs the web server.
  - **model.py**: Contains the machine learning model code for disease prediction.
- **Final Paper.pdf**: The comprehensive report detailing the project's development, methodology, and results.
- **README.md**: This file, providing an overview of the project.
- **LICENSE**: The project's license information.

## Getting Started

To run the application locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/abhinavsaurabh/Disease-Prediction.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Disease-Prediction/WebApp
   ```

3. **Install the required dependencies**:
   Ensure you have Python installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask application**:
   ```bash
   python app.py
   ```

5. **Access the application**:
   Open your web browser and navigate to `http://127.0.0.1:5000/` to use the application.

## Methodology

The project employs machine learning techniques to analyze input data and predict potential diseases. The models were trained on relevant datasets to ensure accuracy and reliability. For detailed information on the data preprocessing, model selection, and training process, please refer to the [Final Paper.pdf](https://github.com/abhinavsaurabh/Disease-Prediction/blob/master/Final%20Paper.pdf).

## Future Enhancements

Potential improvements for this project include:

- **Model Expansion**: Incorporating additional diseases to broaden the application's scope.
- **Data Integration**: Enhancing the model's accuracy by integrating more comprehensive datasets.
- **User Authentication**: Implementing user accounts to allow personalized predictions and data storage.

## Contributing

Contributions to this project are welcome. If you have suggestions for improvements or new features, please fork the repository, create a new branch, and submit a pull request.

## License

This project is licensed under the Apache-2.0 License. See the [LICENSE](https://github.com/abhinavsaurabh/Disease-Prediction/blob/master/LICENSE) file for details.

## Acknowledgments

I would like to express my gratitude to my professors and peers for their support and guidance throughout the development of this project.

---

For more information and to access the codebase, please visit the [GitHub repository](https://github.com/abhinavsaurabh/Disease-Prediction).

---

*Note: This project was developed as part of my undergraduate studies and is intended for educational purposes. It should not be used as a substitute for professional medical advice, diagnosis, or treatment.*
