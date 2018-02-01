# Celery Docker Example 

This is a sample project to demonstrate how to run a Celery task inside a Django project in a Docker container. 

You can read step-by-step instructions here <-- link TBD. 

## Local development setup

Fork this repo into your own GitHub space.

Clone this project as `proj`: 

    git clone git@github.com:[your_username]/celery-docker-example.git proj

Note to add `proj` to the end of the command so it clones onto your machine with a shorter, easier-to-type name.

Make a Python 3.6.x virtual environment and install the dependencies: 

    pip install -r requirements.txt

## Setting up docker-compose 

Using a virtual environment, even when using Docker, is useful so you have easy access to your dependecies and are still isolated from other projects. 

Assuming you have [Docker](https://docs.docker.com/install/) and [docker-compose](https://docs.docker.com/compose/install/) installed, activate your virtual environment and run

    docker-compose up

## Questions?

If you have a question about this project, please consider opening a GitHub Issue. 
