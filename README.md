# javascript-web-htmx-get-mustache-python-flask-api-postgres-simple

## Description
A demo of htmx using a python flask
api to return contents of table from
postgres.

## Tech stack
- htmx
    - get
    - ext
    - swap
    - target
- mustache
- python
    - flask
    - cors
- postgres

## Docker stack
- httpd:latest
- python:latest
- postgres:alpine

## To run
`sudo ./install.sh -u`
- Available at http://localhost

## To stop
`sudo ./install.sh -d`

## To see help
`sudo ./install.sh -h`

## Credit
- [Htmx clientside template](https://htmx.org/extensions/client-side-templates/)
- [Htmx rendering JSON](https://marcus-obst.de/blog/htmx-json-handling)