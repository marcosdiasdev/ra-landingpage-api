# React Avançado - Landing Page - Strapi API

## Prerequisites

- Docker
- PostgreSQL (psql)

## Running the API

Extract the content of `./app/data.zip` and copy the `uploads` directory to `./app/public/uploads`. Then import the extracted SQL file by running `psql -h localhost -U strapi -d strapi -W < strapi.sql` and run `docker-compose up`.
