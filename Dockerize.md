# Dockerizing our app

`Note`: Filename should be `Dockerfile`

## Important and general Dockerfile instructions


### `FROM` : Base image (like node)

the base image mainly the coding environment we are working in like node, Java, python

---

### `WORKDIR` < path >
Define working directory, all the next commands will be executed here and all the files will be copied here

---

### `COPY` < host-path > < image-path >

---

### `RUN` : Running a command in image shell

---

### `CMD` : Similar to RUN but only one in the Docker file mainly used to run the project

`Note` : A Dockerfile may have multiple run commands like `npm i` & `npm build` but single `CMD` command

--- 

### `EXPOSE` : Expose port of an image

### `ENV` : Environment variables

---

## Build commands

```
docker build -t nodeapp:1.0 .
```