#create a directory
$ mkdir Flask

cd Flask

#create your virtual environment in your directory

$ virtualenv  venv

#activate your virtual environment
$ source venv/bin/activate

#define variables to use during development
$ export FLASK_APP="run.py"
$ export SECRET="mamamilka"
$ export APP_SETTINGS="development"
$ export DATABASE_URL="postgresql://localhost/flask_api"



