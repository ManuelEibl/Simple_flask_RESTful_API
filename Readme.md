# Simple Flask RESTful API
This is a simple exemplary dockerized RESTful Flask API.

## How to run
Can be run from inside of WSL2 and accessed on Windows OS.
```bash
docker build -t flask_app .
docker run -dp 5000:5000 flask_app 
´´´