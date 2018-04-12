# Rebilly/ReDoc Docker image
Container with Rebilly/ReDoc - OpenAPI/Swagger-generated API Reference Documentation

# how to run

## with pet example

    docker run -i \
        -p 80:80 \
        -t marciocamurati/redoc

## with custom swagger.yaml

You need a folder where your `swagger.yaml` is placed.
It has to be named `swagger.yaml`.

    docker run -i \
        -p 80:80 \
        -v /path/to/folder:/usr/share/nginx/html/data \
        -t marciocamurati/redoc

# references

* [Rebilly/ReDoc](https://github.com/Rebilly/ReDoc)
