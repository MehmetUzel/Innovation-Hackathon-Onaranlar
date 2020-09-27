# Innovation-Hackathon-Onaranlar
Onaranlar Website
## Setup

1. Git Clone the project

2. Move to the base directory: ```cd Onaranlar-Website```

3. Create a new python enveronment with: ```python -m venv env```.

4. Activate enveronment with: ```env\Scripts\activate``` on windows, or ```source env/bin/activate``` on Mac and Linux.

5. Install required dependences with: ```pip install -r requirements.txt```.

6. Make migrations with: ```python manage.py makemigrations``` and then ```python manage.py migrate```.

7. Run app localy with: ```python manage.py runserver```.

8. Use this link to open website "http://127.0.0.1:8000/"

To use admin page you should add "/admin" at the end of url
