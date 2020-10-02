# teach-docker

Objective: Build the docker image and run it, you should see 
"Hello world!" when you visit http://127.0.0.1:8081 in your 
web browser.


# How to build


```
docker build -t helloworld .
```

# How to run

```
docker run -p 8081:8081 helloworld
```
