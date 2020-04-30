# Full-Stack ToDo Web App with Python
This is a project for a Clever Programmer's course.

## Contents

1. [Initial Setup Instructions](#initial-setup-instructions)
1. [Running Server](#running-server)


## Initial Setup Instructions

### Setup Python Virtual Environment
```buildoutcfg
python3 -m venv venv
. venv/bin/activate
pip3 install -r requirements.txt
```
## Running Server
### Cheatsheet
```buildoutcfg
sqlite3 todo.db <---- creates db and runs sqlite3 terminal
.tables <---- saves db in sqlite3 terminal
.exit <------ closes sqlite3 terminal
python / python3 <---- run python terminal
from app  import  db <----- import db from our flask app inside python terminal
db.create_all() <---- creates tables
exit() <----- exit from terminal
python app.py <---- run our app
```
### Go and check `http://127.0.0.1:5000`
