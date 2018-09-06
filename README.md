# Simple Hello World app with NodeJS
Just a sample app to test nodejs

## Setup

Just run docker commands.

```bash
docker build -t hello-node:v1 .
docker run -d -p 8080:8080 hello-node:v1

```

App is now running on [http://localhost:8080](http://localhost:8080).