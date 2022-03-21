# gistapi

Gistapi is a simple HTTP API server implemented in Flask for searching a user's public Github Gists. 
# Running the app

```bash
# Directly
python -m gistapi.gistapi

# Via gunicorn
gunicorn gistapi.gistapi:app

# Via Docker
docker build . -t flask-app
docker run -p 8000:8000 flask-app

# Via docker-compose
docker-compose up
```
