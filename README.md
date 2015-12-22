# Rails On Docker Example

## dependency
* Docker
* Docker-Compose
* Rails 4.2.5
* Ruby 2.2.0
* mysql 5.6.23
* nginx 1.7.9


### Usasge
Build Containers
```bash
$ docker-compose build
```

Run for Rails Environment Task
```bash
$ docker-compose run rails rake db:create
$ docker-compose run rails rake db:migrate
$ docker-compose run rails rake assets:precompile
```

lanuch Containers
```bash
$ docker-compose up
```
