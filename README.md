# Email Spam Detection

A simple web-based Email Spam Detection application built using Python and Django. It allows users to enter a message and check whether it is classified as **Spam** or **Not Spam**.

## Features

- Simple and user-friendly web interface
- Text input form for entering messages
- Spam and Not Spam classification results
- Django-based web application
- Easy to run locally

## Tech Stack

- **Language:** Python
- **Web Framework:** Django
- **Frontend:** HTML, CSS
- **Form Handling:** Django Forms
- **Machine Learning:** Scikit-learn (if used in the prediction pipeline)

## Project Structure

```text
Spam-Detector/
├── detector/
│   ├── templates/
│   │   └── home.html
│   ├── forms.py
│   ├── views.py
│   ├── urls.py
│   └── models.py
├── spamDetection/
│   ├── settings.py
│   └── urls.py
├── manage.py
├── db.sqlite3
└── README.md
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/ayush-bansal12/Spam-Detector.git
cd Spam-Detector
```

### 2. Create a virtual environment

For macOS or Linux:

```bash
python3 -m venv myenv
source myenv/bin/activate
```

For Windows:

```bash
python -m venv myenv
myenv\Scripts\activate
```

### 3. Install dependencies

```bash
python -m pip install django pandas scikit-learn
```

### 4. Run database migrations

```bash
python manage.py migrate
```

### 5. Start the development server

```bash
python manage.py runserver
```

Open the application in your browser:

http://127.0.0.1:8000/

## How to Use

1. Open the application in your browser.
2. Enter a message in the text area.
3. Click the **Check Message** button.
4. View the classification result displayed by the application.

## Project Objective

The objective of this project is to demonstrate a basic web application for identifying spam messages and to understand how web technologies can be used for text classification.

## Future Improvements

- Integrate and evaluate a trained machine learning model.
- Improve the user interface.
- Display model accuracy and evaluation metrics.
- Add a history of previous predictions.

## Author

Ayush Bansal

## License

This project was developed for educational and college lab purposes.

## Live Demo

Try the deployed application here:

**[Spam Detector — Live Website](https://spam-detector-3le4.onrender.com)**

## Features
- Email/message spam detection
- Machine learning-based classification
- Django web interface
