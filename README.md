# python-web-api-flask-traefik-sqlserver-ssl-simple

## Description
Creates an api of `dog` for a flask project.
Has the ability to query by parameters.
If path is not found, will default to 404 error.
Uses self-signed ssl.

Sql server uses self-signed ssl.

## Tech stack
- python
- flask
- sql server
- reverse proxy
- ssl

## Docker stack
- alpine:edge
- alpine:edge
- python:latest
- traefik:v2.4
- mcr.microsoft.com/mssql/server:2017-CU17-ubuntu

## To run
`sudo ./install.sh -u`
- Endpoint
  - [Available](https://myapi.docker.localhost/dog)

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://stackabuse.com/using-sqlalchemy-with-flask-and-postgresql/
- https://stackoverflow.com/questions/27766794/switching-from-sqlite-to-mysql-with-flask-sqlalchemy
