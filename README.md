# graphql-python
A Hacketnews project using Python, Django and Graphene. 

## Installation and Usage
Clone the project.

Create a virtual environment:
```bash
python3.6 -m venv venv
source venv/bin/activate
```

Install everything needed:
```bash
pip install -r requirements.txt
```

Create the database and run the server:
```
python hackernews/manage.py migrate
python hackernews/manage.py runserver
```
