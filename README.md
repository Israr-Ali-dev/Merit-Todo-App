# Merit TODOs Project

## How to setup project?

### --------- BACKEND ---------

### Clone the project from Github

git clone this project or download the project to your computer locally

### Install Docker-Compose on Your Local System

Download URL : https://docs.docker.com/compose/install/

### Start the server (Build & Up the docker images)

```sh
docker-compose up -d --build
```

### Run a migration

```sh
docker-compose exec backend alembic upgrade head
```

### View the API Documentation (This will ensure the server is running)

1. Open your web browser of choice
1. In the URL enter: http://0.0.0.0:3000/docs

### --------- FRONTEND ---------

### Move to Frontend Folder

```sh
cd ../frontend
```

### Install All Packages

```sh
npm install
```

### Run Application

```sh
npm start
```

Developed by: Israr Ali
