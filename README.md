# Multi-Container Docker Application
This project uses Docker Compose to set up a multi-container environment for a JS TODO Application and MongoDB. Below are the steps to clone the repository, build the containers, and run the application.



## Prerequisites

Before you start, ensure you have the following installed:

- Docker: Install Docker
- Docker Compose: Install Docker Compose

### Setup Instructions
1. Clone the Repository
```bash
git clone https://github.com/MZain-ul-Abideen/multi-contain-TODO-app.git
cd multi-contain-TODO-app
```
2. Build the Docker Containers
```bash
docker-compose build
```
3. Run the Containers in Detached Mode
```bash
docker compose up -d
```
4. Watch Mode (Optional)

If you want to enable live reloading to track changes for the todo-app container, run the following command:
```bash
docker compose watch
```

5. Access the Application
```bash
http://localhost:3000
```

6. Stopping the Containers
```bash
docker compose down
```

