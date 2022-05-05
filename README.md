# PgAdmin

## Requirements

* docker
* docker-compose

## Start

* `docker-compose up -d`

## Environments

This Compose file contains the following environment variables:

| ENV             |  Description                                                   | Value                | Required  |
|---|---|---|---|
| PGADMIN_PORT                | pgAdmin port                                       | 5050                 | false     |
| PGADMIN_DEFAULT_EMAIL       | Email                                              | pgadmin4@pgadmin.org | false     |
| PGADMIN_DEFAULT_PASSWORD    | Default password                                   | admin                | false     |

## Access

* **URL:** `http://localhost:5050`
* **Username:** pgadmin4@pgadmin.org
* **Password:** admin
