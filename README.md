# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

# Install

参考にした記事

* https://zenn.dev/toono_f/scraps/e7346c6e90c35b
* https://zenn.dev/wakkunn/articles/33c84147608078


```
$ docker compose build --no-cache
$ docker compose run --rm web rails new . --force --database=mysql --api
$ docker compose up
$ docker compose exec web rails db:create
```

# 動作確認

http://localhost:3000/

# ですとろーい

```
$ rm -rf Rakefile app bin config config.ru db lib log public storage test tmp vendor
```