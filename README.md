Alphabet Classifier

📌 Project Overview

This is an Alphabet Classification Web App that uses a deep learning model to predict both uppercase (A-Z) and lowercase (a-z) alphabets from images. The model is deployed using Flask and provides a user-friendly interface for uploading and classifying images.

🚀 Features

Upload an image of a handwritten or printed alphabet.

Preview the uploaded image before classification.

Predicts both uppercase and lowercase letters.

Displays the predicted alphabet with confidence score.

Simple and responsive UI using HTML, CSS, and JavaScript.

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript

Backend: Flask (Python)

Deep Learning Model: TensorFlow/Keras

Deployment: Flask Web Server

Version Control: Git & GitHub

📂 Folder Structure

Alphabet-Classifier/
│── app.py                     # Flask backend
│── alphabet_classifier.keras  # Trained model file
│── static/                    # Static files (CSS, JS, images)
│── templates/                 # HTML templates
│   ├── index.html             # Main UI page
│── images/                    # Folder to store uploaded images
│── README.md                  # Project documentation
│── requirements.txt           # Required dependencies

⚙️ Setup and Installation

Clone the repository

git clone https://github.com/your-username/alphabet-classifier.git
cd alphabet-classifier

Create a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install dependencies

pip install -r requirements.txt

Run the Flask App

python app.py

The app will run on http://127.0.0.1:5000/.

🖼️ How to Use

Open the web app in your browser.

Click on Upload an Image and select an alphabet image.

Click Classify Alphabet to get the predicted result.

The model will display the detected alphabet along with a confidence score.

📢 Contributing

Feel free to fork the repository, make improvements, and submit a pull request. Any contributions are welcome!

⚖️ License

This project is open-source and available under the MIT License.
