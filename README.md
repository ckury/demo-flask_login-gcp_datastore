# Flask-Login demo with data hosted in Google Cloud Datastrore
This repo contains a demo of using flask-login with Google Cloud datastore as the storage method for credentials with the flask app running stateless in a cloud run service. This would be the equivalent of running the app with each request having it's own running environment separate from other requests. Any data to be stored will be in Google Cloud Datastore

## Running the demo
1. Install Google Cloud CLI
2. Authenticate Google Cloud CLI with account and project
4. Clone repository
5. Install requirements with `pip -r requirements.txt`
6. Run `main.py` with python version 3.11 or above
