# MacOS

```
$ git clone git@github.com:dongri/hello-rust.git
$ cd hello-rust
$ cargo build
$ cargo run
  Running `target/debug/hello`
```

open http://localhost:8080

# Docker for mac

```
$ cd hello-rust
$ docker-compose up
```

open http://localhost:8080

# Heroku

```
$ heroku plugins:install heroku-container-tools
$ heroku create
$ heroku container:login
$ heroku container:push web
```

open https://***.herokuapp.com
