1. Building Docker Image

```
docker build -t igniterab/resumeupload-ui:latest .
```


2. Push the Docker image in your account

3. Running the ui

```
    docker pull igniterab/resumeupload-ui:latest
    docker run -dit -p 4200:4200 igniterab/resumeupload-ui:latest

```