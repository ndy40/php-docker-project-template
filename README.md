# php-docker-project-template
A simple project folder for easily adding docker to any PHP project irrespective of framework. 

Simply create your php folder and drop them in the `app` folder at the root. 
The project expects to your php project to have a `public` folder since the nginx 
configured here will be expecting the root to live at `app/public`. 

Configuration files for *nginx*, *mysql* and *php* live in the `docker/php`, `docker/nginx`
and `docker/mysql`. 

The environment file `.env-example` contains placeholder for important variables needed by docker. 
Rename the file to `.env`. 

# Note: 
This project at the moment is only setup for quick easy local development.

TODO: 
- [ ] Add configuration file for Mysql. 
- [ ] Add setup for Redis cache
- [ ] Add production version of the `docker-compose.yml`
- [ ] Add support for XDebug

