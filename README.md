# Usage

```
$ git clone git@github.com:mochizukikotaro/docker-rails-mysql.git; cd $(basename $_ .git)

$ docker-compose build

$ docker-compose run web rails db:create
>password

$ docker-compose up
```

Access `localhost:3000`, and see

![2017-03-05 17 06 23](https://cloud.githubusercontent.com/assets/7911481/23585614/1fb8ccb4-01c6-11e7-8c97-b6ed781d014f.png)
