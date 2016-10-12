### Implementing JSON API in a Rails 5 API

http://www.thegreatcodeadventure.com/building-a-super-simple-rails-api-json-api-edition-2/

### Tools

Rails 5.0.0.1

Docker

### Docker Cheatsheet

- build docker image based on Dockerfile

  - docker-compose build

- spin up and connect containers as directed in docker-compose.yml

  - docker-compose up -d

- run standard rails commands

  - docker-compose run app bundle install

  - docker-compose run app rails console

  - docker-compose run app rake routes

  - docker-compose run app rake db:reset db:migrate

  - docker-compose run app rake db:seed