# Spam Email and SMS Classifier

This repository contains a Spam Classifier that can classify email and SMS messages as spam or not spam. It uses machine learning to make predictions based on the provided input.

## Project Structure

- **`sms_spam_detection.ipynb`**: A Jupyter notebook that trains the spam detection model and generates the necessary files (`model.pkl` and `vectorizer.pkl`).
- **`app.py`**: A Python script to launch the web application for interacting with the spam classifier.

## Getting Started

Follow the steps below to set up and run the project on your local machine.

### Prerequisites


- Python 3.8 or later
- Required libraries:
  - Flask
  - Scikit-learn
  - Pandas
  - Numpy
  - Jupyter Notebook

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Nishaad27/Sms-Email-Spam-Classifier.git
   cd Sms-Email-Spam-Classifier
   ```

2. Install the dependencies:
   ```bash
   pip install flask scikit-learn pandas numpy jupyter
   ```

### Training the Model

1. Open the Jupyter notebook `sms_spam_detection.ipynb` in your preferred environment (e.g., Jupyter Notebook, VS Code, or Google Colab).
2. Run all the cells to train the spam detection model.
3. Upon successful execution, the following files will be generated:
   - `model.pkl`: The trained model file.
   - `vectorizer.pkl`: The text vectorizer used for preprocessing input.

### Launching the Web App

1. Run the `app.py` script to start the web application:
   ```bash
   python app.py
   ```

2. Open a web browser and navigate to the URL provided in the terminal (typically `http://127.0.0.1:5000/`).
3. Use the web interface to classify SMS or email messages as spam or not spam.

## Project Files

- **`model.pkl`**: Trained machine learning model.
- **`vectorizer.pkl`**: Vectorizer for preprocessing text data.
- **`app.py`**: Flask web application.
- **`sms_spam_detection.ipynb`**: Notebook for training and saving the model.

## Technologies Used

- **Python**: Core programming language.
- **Machine Learning**: Scikit-learn for training the spam classifier.
- **Flask**: Web framework for the application.

## Contributing

Feel free to open issues or submit pull requests if you'd like to contribute to this project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

Special thanks to everyone who contributed to the open-source libraries used in this project.
