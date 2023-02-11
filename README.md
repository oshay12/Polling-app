to run polling application:

in terminal, set your current directory to the project directory where the manage.py file is located (cd "path/to/project/directory")

after this is complete, run the command:

    MAC:
        python3 manage.py runserver

    Windows:
        python manage.py runserver

this should start the development server for use. click the link that shows up in the terminal (ex. "Starting development server at http://127.0.0.1:8000/") and add "polls" to the end to access the available polls (http://127.0.0.1:8000/polls) or add "admin" to perform administrative tasks on the application like adding new polls to the list (http://127.0.0.1:8000/admin)

