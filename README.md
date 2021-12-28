# Open Minds - Django Blueprint - CookieCutter template
### API available and running in Containers

OpenMinds is the "umbrella name" for my pet projects :-) - [OpenMinds.zone](http://openminds.zone)

## Project description
The goal of this project is to provide a fast and easy way to quickly bootstrap a new Python / Django project, ready for you to start working on the specificities of your project.  
Instead of keep repeating the same boilerplate over and over.  
And at the same time, providing basic security and industry good practises.

### Django project is structured on front-end / back-end logic.
The goal is to use an independent client application for front-end, interacting with Django back-end via API, using Django Rest Framework.  
However, classical monolithic approaches via Django views and templates are still available.

## How to use
- You have to have CookieCutter installed.
  - If you don't, please do `pip install cookiecutter`  
  - It should be done on your global Python namespace.
    Once is a tool to be used across several projects.
  - For complete information, please refer to CookieCutter documentation: [https://cookiecutter.readthedocs.io/](https://cookiecutter.readthedocs.io/)
- Install from repository: `cookicutter https://github.com/rtavares/OM-DjangoBluePrint-API-Conteinerized-cookiecutter-template.git`
- Alternatively, you can clone the repository - `git clone https://github.com/rtavares/OM-DjangoBluePrint-API-Conteinerized-cookiecutter-template.git` - locally, make some adjustments if you want to, and then run:
  - `cookiecutter [path-to-your-local-template-repository]`

## Technical stack
- `Django Blueprint CookieCutter Template`  has been designed to work on `Python 3.10` and `Django 4`  
  - You can customise it for your specific needs before bootstrapping your new project.
- Project virtual environment is managed by [Poetry](https://python-poetry.org/)  
  - Also have to be installed globally.
  - However, you are free to choose any virtual environment manager you may prefer, onde we will be providing a `requirements.txt` file.    
- We use:
  - `make` to make our life easier.
  - `.env` files to handle secrets.
- Containerization aims to support `podman` and `Docker`.

## Features
Please refer to project README.  
Different from CookieCutter Template project README - this file.

---------------------