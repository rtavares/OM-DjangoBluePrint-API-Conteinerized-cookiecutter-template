# Project {{cookiecutter.project_name}}
Bsed on  [Open Minds - Django Blueprint - CookieCutter template](https://github.com/rtavares/OM-DjangoBluePrint-API-Conteinerized-cookiecutter-template)  

OpenMinds is the "umbrella name" for my pet projects :-) - [OpenMinds.zone](http://openminds.zone)

## Description
The goal for this project is to have a basic Django project, ready to run, easy to customize, and respecting security and industry good practices.

## Technical stack
- `Django Blueprint CookieCutter Template`  has been designed to work on `Python 3.10` and `Django 4`  
  - You can customise it for your specific needs before bootstrapping your new project.
- Project virtual environment is managed by [Poetry](https://python-poetry.org/).  
  - Also have to be installed globally.
  - However, you are free to choose any virtual environment manager you may prefer, onde we will be providing a `requirements.txt` file.    
- We use:
  - `make` to make our life easier.
  - `.env` files to handle secrets.
- Database - PostGreSQL with fallback to SqlLite.
- Containerization aims to support `podman` and `Docker`.

----------------

