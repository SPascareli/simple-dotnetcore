# Description

This is a simple DotNet Core API running in Docker, with monitoring provided by Prometheus and Grafana.

# How to run

To see the API in action, simply do a `docker-compose up -d` from the project root dir, it will build a local image of the API,
with a prometheus and grafana containers.

API: http://localhost:5000

Grafana: http://localhost:3000

Prometheus: http://localhost:9090


***Obs**: The first time you access grafana, use the 'admin' user with the 'admin' password, you will be propmted to redefine it.*

## Running in development

To develop in the API code, use the `dotnet restore` command followed by `dotnet run` to run the API outside of docker.
