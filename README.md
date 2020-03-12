


https://overiq.com/flask-101/application-structure-and-blueprint-in-flask/
https://github.com/overiq/flask_project


G:/2020_working/coding/flask_application_structure_blueprint/

cd /mnt/g/2020_working/coding/flask_application_structure_blueprint/
conda deactivate
python3 -m venv env
source env/bin/activate

mkdir app
touch app/__init__.py
mkdir app/static
mkdir app/templates
touch app/views.py
touch config.py
touch runner.py
mkdir app/templates/
touch app/templates/index.html


 tree -I '.git|env'
--------------------------------------------------------------------------------
 .
├── README.md
├── app
│   ├── __init__.py
│   ├── forms.py
│   ├── models.py
│   ├── static
│   ├── templates
│   ├── utils.py
│   └── views.py
├── config.py
└── runner.py
--------------------------------------------------------------------------------
pip install Flask-Script
pip install Flask-Migrate
pip install Flask-Mail
pip install Flask-WTF


python runner.py runserver

http://127.0.0.1:5000/
