# Usage

```
$ git clone git@github.com:mochizukikotaro/docker-rails-mysql.git; cd $(basename $_ .git)

$ docker-compose build
$ docker-compose up -d

$ docker-compose exec app bundle install
$ docker-compose exec app rails db:create >password
$ docker-compose exec app puma

# Docker attach
$ docker-compose exec -d app puma
```


Access `localhost:3000`, and see


<img width="694" alt="2017-05-04 14 27 24" src="https://cloud.githubusercontent.com/assets/7911481/25691452/ffb03b20-30d5-11e7-8a77-cdce940b3b10.png">
