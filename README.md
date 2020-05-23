# Django Project Boilerplate

This repository is a boilerplate Django project for quickly getting started.

[![alt text](https://github.com/justdjango/django_project_boilerplate/blob/master/thumbnail.png "Logo")](https://www.youtube.com/watch?v=GEogao-tUec)

## Getting started

Steps:

1. Clone/pull/download this repository
2. Create a virtualenv and install dependencies:
   ```bash
   python -m venv env
   source env/bin/activate
   python -m pip install -r requirements.txt
   ```
3. Copy the `.env.example` file to `.env` and configure your variables
4. Rename your project with `./manage.py rename <yourprojectname> <newprojectname>`

This project includes:

1. Settings modules for deploying with Azure
2. Django command to rename your project
3. A cli tool for setting environment variables for deployment
