# Simple Flask App

A minimal Flask app containerized with Docker.

## Run Locally

pip install -r requirements.txt
python app.py

## Run with Docker

docker build -t simple-flask-app .
docker run -p 5000:5000 simple-flask-app

Visit: http://localhost:5000

