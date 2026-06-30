# Flask Devops Lab
## Usage
This project creates a web server using flask and deploys it in a docker container. It also uses best practices for git. 

You must create a venv locally to use this application.

To activate the venv and run the application
```
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

## Routes
There are three different routes in this project

/api/health

Shows the health of the project

/api/config

Shows the project's configuration 

/api/report

Will contain reports related to the application