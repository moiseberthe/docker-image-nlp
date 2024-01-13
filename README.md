# Docker project with Streamlit, FastAPI and SQLite

## Prerequisites

Make sure you have `Docker` and `Docker Compose` installed on your machine.

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Clone project

```bash
git clone https://github.com/moiseberthe/docker-image-nlp.git
```

## Docker setup

The `docker-compose.yml` file contains the Docker configuration for the services.

### Build and run containers

```bash
docker compose up --build
```

The project will be accessible at the following address:

- Streamlit: [http://localhost:8501](http://localhost:8501)
- FastAPI: [http://localhost:8000](http://localhost:8000)