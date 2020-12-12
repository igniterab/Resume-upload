1. Building Docker Image

```
docker build -t igniterab/resumeupload-be:latest .
```


2. Push the Docker image in your account

3. Running the backend

```
    docker pull igniterab/resumeupload-be:latest
    docker run -dit -p 3000:3000 igniterab/resumeupload-be:latest

```