# Documentation

This directory contains the code for generating the project documentation site. The documentation site is generated with [Jekyll](https://jekyllrb.com/).

## Running locally

A Docker Compose service is provided at the root of the repo for running the preview server locally.

```
docker-compose up docs # Docs should be accessible at http://localhost:4000
```

## Running commands

Commands can be run in the container to update gems, build the static Jekyll output etc.

Examples:
```
docker-compose run docs bundle update
docker-compose run docs jekyll build
```
