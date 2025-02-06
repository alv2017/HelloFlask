# Hello Flask

Project goals: 
- create a simple Flask application
- demonstrate how to use uv in Docker container
- demonstrates the basics of setting the Gunicorn WSGI server
- demonstrates how to set a reverse proxy server in front of the WSGI server

Introductory Flask project is taken from CS50 course series.

Reference: https://www.youtube.com/watch?v=1r-dFbPQ7Z8&list=PLhQjrBD2T383q7Vn8QnTsVgSvyLpsqL_R&index=13


## Running the App

```
flask --app app run 
```


## Running the App in the DEBUG Mode

When you run the app in the DEBUG mode, the app automatically restarts if the code is changed

```
flask --app app run --debug
```


## Running the App in Docker

Start application inside the docker container:

```
docker compose up
```

Rebuild and run the application inside the docker container:

```
docker compose up --no-deps --build
```

Now you can open the Flask app on http://127.0.0.1 


Stop the docker container:

```
docker compose down
```


