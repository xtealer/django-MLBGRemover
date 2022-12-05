# django-MLBGRemover

A Machine Learning Project integrated with Django to Remove Background from Images.

## Installation:

- git clone https://github.com/xtealer/django-MLBGRemover
- cd django-MLBGRemover
- python3 -m pip install -r requirements.txt
- bash setup.sh
- python3 manage.py migrate
- python3 manage.py runserver

### Supported OS:

- Linux

### For API Usage:

Make a POST request to http://localhost:8000/upload with the Following parameters.
image=[BASE64 ENCODED IMAGE HERE]
