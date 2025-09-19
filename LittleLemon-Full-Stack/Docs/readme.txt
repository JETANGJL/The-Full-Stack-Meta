Use the following command in terminal to review:

cd <project directory>

pipenv shell

pipenv install 

python manage.py makemigrations

python manage.py migrate

python manage.py runserver

Django spins up its development server (usually at http://127.0.0.1:8000/).

While the server is running, you can visit:
http://127.0.0.1:8000/book/ 
in your browser to see your Book a Table form.

If you stop the server (Ctrl + C in terminal), 
the link will no longer work because the server isn’t serving your app anymore.

Thankyou for your time!
