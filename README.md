# Email Spam Detection

A web-based Email Spam Detection application built using Python and Django. It allows users to enter a message and classify it as **Spam** or **Not Spam** through a simple web interface.

## Live Demo

**[Open Spam Detector — Live Website](https://spam-detector-3le4.onrender.com)**

## Features

- Simple and user-friendly web interface
- Text input form for entering messages
- Spam and Not Spam classification results
- Django-based web application
- Machine learning-based text classification
- Easy to run locally

## Tech Stack

- **Programming Language:** Python
- **Web Framework:** Django
- **Frontend:** HTML, CSS
- **Form Handling:** Django Forms
- **Data Processing:** Pandas
- **Machine Learning:** Scikit-learn

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
├── emails.csv
├── requirements.txt
├── db.sqlite3
└── README.md
```

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/ayush-bansal12/Spam-Detector.git
cd Spam-Detector
```

### 2. Create a Virtual Environment

**macOS or Linux:**

```bash
python3 -m venv myenv
source myenv/bin/activate
```

**Windows:**

```bash
python -m venv myenv
myenv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Database Migrations

```bash
python manage.py migrate
```

### 5. Start the Development Server

```bash
python manage.py runserver
```

Open the following URL in your browser:

http://127.0.0.1:8000/

## How to Use

1. Open the application using the live demo link or run it locally.
2. Enter a message in the text area.
3. Click the **Check Message** button.
4. View the classification result displayed by the application.

## Project Objective

The objective of this project is to demonstrate how Python, Django, and text classification techniques can be used to build a web-based application that identifies spam messages.

## Future Improvements

- Improve the accuracy of spam detection.
- Display model accuracy and evaluation metrics.
- Enhance the user interface.
- Add a history of previous predictions.
- Evaluate the model on additional datasets.

## Deployment

The application is deployed using Render.

**Live Application:** https://spam-detector-3le4.onrender.com

## Author

**Ayush Bansal**

## License

This project was developed for educational and college laboratory purposes.
