I made this project while following this tutorial https://www.youtube.com/watch?v=F5OUT3ijk8M&t=3812s&ab_channel=BekBrace
His code for this project also can be found at https://github.com/BekBrace/django-react-app-Task_Manager. There are a little bit of slight differences between his github and youtube version in term on UI.

Pre-req 
- Python 3.xx.
- pipenv (Great tool to create virtual environment. To install just do "pip install pipenv".)

1. Cd into backend folder, install dependencies, and run virtual environment.
do "pipenv install" - This will install all needed dependencies such as restframework and cors-headers.
do "pipenv shell"

4. Run backend server.
Do "python manage.py runserver". Please note that django is full backend here. Apart from that, the backend implements restframework which provides UI for the apis. To access the api, please go to http://localhost:8000/api/tasks/.

5. Run frontend server.
I believe you can just do npm start. The website should automatically opens. If not, please visit http://localhost:3000/. Also, please make sure the backend server is running. 

Have fun hacking :P

Things I am planning to implement:
- Multipage application
- Deployment of this application to linux web server.
- Graph