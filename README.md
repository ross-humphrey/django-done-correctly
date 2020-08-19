## mod_wsgi-express
Better suited for using Apache and mod_wsgi within a docker container. Which 
is what we are trying to achieve here.

Can be run using

`python manage.py runmodwsgi`

OR (to reload changes in development

`python manage.py runmodwsgi --reload-on-changes`


## Docker
The Dockerfile and docker-compose.yml define how to run this project in docker

To compose and build the services use:

`docker-compose-up` 
This will run the django app using the docker file

To view containers
`docker ps`

To bring application down
`docker-compose down`
