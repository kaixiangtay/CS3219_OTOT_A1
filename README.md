# CS3219_OTOT_TaskA1

**Pre-requisites: Docker software installed on computer**

Step 1: Clone the project repository onto your local computer.

Step 2: Open up the Terminal and inside the project folder directory,
 execute the following command to build the Docker images:

```
docker-compose build
```

Step 3: Next, execute the following command to  run the Docker container which contains the Docker images:
```
docker-compose up -d
```

Step 4: Open a new window in any browser and enter `http://localhost` or `http://localhost:5001`to load the static HTML webpage.

**Note: Repeat Steps 2, 3 whenever any changes is being made to the project so that Docker images can be rebuild and Docker container can be recreated.**
