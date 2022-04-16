# Scalable Architecture Demo

A cookiecutter template for bootstrapping a Go and React project using a
modern stack.

## Run the server with:

```bash
go run main.go
```

## Container build:

```bash
docker build --tag goapp .
```

## Run the container:

```bash
docker run --rm -p 8080:8080 goapp
```

```bash
docker run --rm --name goapp -p 8080:8080 goapp
docker container run -it goapp
docker run -it --rm --name goapp -p 8080:8080 goapp bash
```
