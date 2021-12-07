# postgres-todo

Example PostgreSQL TODO CRUD CLI application for tutorial purposes. The app
uses the `typer` CLI (Command Line Interface) library to perform
CRUD (Create, Read, Update, Delete) operations against a PostgreSQL database.

## Blog posts that use this application

- Build and test a FastAPI postgres recipe API
- My top linting tools for a python app
- Run GitHub actions pipeline to lint and test a Postgres application
- Run GitLab-CI pipeline to lint and test a Postgres application

## Specifications

This app runs on python 3.9+ with a Postgres Database version of 13+.
There is a script for creating a local Postgres docker container for
convenience, but you can also install postgres locally or use a remote
postgres instance.

## Installing python packages

You can create a python virtual environment with `python3.9 -m venv venv`
(in some environments `python -m venv venv`). Activate your virtual environment
with `source venv/bin/activate` (`source venv/Scripts/activate`
in git bash for windows). In an activated python 3.9 virtual environment,
first update pip packages with `pip install --upgrade pip`. Then install
this project's dependencies with `pip install -U -r requirements.txt`.

## Code lint

TODO

## Starting a local Postgres database with docker

TODO

## Running the API

TODO

## Using the API

TODO

## Testing the API

TODO

## CI
