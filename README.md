# Prototype
This is the prototype of my coursework project. Please read the "Setup and Installation" section to get started.

## Prototype Code for Coursework.
Only some of the planned tables are currently in this version of the system. In this prototype I am focusing on making new users, authenticating existing users, adding new classes and adding students to classes.

## Setup and Installation
### For Testing and Assessment
1. Ensure python 3.6 or greater is installed.
2. Open CMD on Windows, or a terminal on Linux.
3. Navigate to the prototypes directory. (By default this document is contained in it.)
4. If you wish to use a virtual enviroment run `python -m venv ./venv` and then `./venv/Scripts/activate.bat` on Windows, or `./venv/Scripts/activate` on Linux.
5. Run `pip install -r requirements.txt` to install the requirements for this program.
6. Run `python setup-database.py` to initialize the database.
7. Run `python run.py` to run the server.
8. Open a browser and navagate to `localhost:5000`.

### For Hosting and Deployment
Sorry, the prototype is not currently built for release and deployment.
