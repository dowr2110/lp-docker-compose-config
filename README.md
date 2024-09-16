# README

This is the docker-compose configuration file, in which it is possible to run the entire microservice

Things you may want to cover:

* Create .env files in each app (lesson-planer and lp-analytics_service)
* run `docker-compose up --build`
* run `docker-compose exec main_app rails db:create`
* run `docker-compose exec main_app rails db:migrate`
* run `docker-compose exec main_app rails db:seed` if database is empty
* run `docker-compose exec main_app rake elasticsearch:reindex`
* get into the container `docker-compose exec -t main_app sh` and then run any rails commands. For example: `rails c`
* run worker in lp-analytics-service `docker-compose exec analytics_service rake worker:start_analytics_worker`