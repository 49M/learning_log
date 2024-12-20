This is my first ever Django web application project! 
Following along with Python Crash Course 3ed, and making some personalized edits, I have created a learning log web app which helps users track their 
learning. Users can create accounts and input data (notes) on whichever subject they are learning. This app simplifies
the note-taking process for students or self-interested learners through a simple framework, making tracking easy!

How to run instructions:
- Install python and Django (https://docs.djangoproject.com/en/5.1/topics/install/)
- Open the project in an editor of your choice example: VScode.

Unix/MacOS:
- Create a virtual environment: "python -m venv <name-of-environment>"
- Type into the terminal: "source <name-of-environment>/bin/activate", to activate the virtual environment

Windows:
- Create a virtual environment: "py -m venv <name-of-environment>"
- Type into the terminal: "<name-of-environment>\Scripts\activate.bat", to activate the virtual environment


- With an active environment, type: "python manage.py migrate"
- Then to run the server, type into the terminal: "python manage.py runserver"
- Paste into a search engine http://localhost:8000/ to use the web application
- To stop running the program, Control-C and type "deactivate" in the terminal
