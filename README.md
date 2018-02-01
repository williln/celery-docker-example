# Celery Docker Example 

This is a sample project to demonstrate how to run a Celery task inside a Django project in a Docker container. 

You can read step-by-step instructions here <-- link TBD. 

## Running the project locally 

Uses [`pyenv-virtualenvwrapper`](https://github.com/pyenv/pyenv-virtualenvwrapper). 

1. Fork this repo into your own GitHub space
2. `cd` into the directory where you keep Git projects 
3. `git clone git@github.com:[your_username]/celery-docker-example.git`
4. `mkvirtualenv [env_name] --python==python3.6`
5. `workon [env_name]`
6. `cd celery-docker-example`
7. `setvirtualenvproject`
8. `docker-compose up` 
9. See output in terminal! 