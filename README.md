# Sidekiq.cr Heroku Buildpack

Heroku build pack to compile and run your [sidekiq.cr](https://github.com/mperham/sidekiq.cr) workers.
Depends on [heroku-buildpack-crystal](https://github.com/crystal-lang/heroku-buildpack-crystal).

## Usage

```
$ heroku create my-app --buildpack https://github.com/crystal-lang/heroku-buildpack-crystal.git
$ heroku buildpacks:add https://github.com/veelenga/heroku-buildpack-sidekiq.cr
```

## Prerequirements

In order for the buildpack to work properly you should have a `src/sidekiq.cr` file.
See [Getting Started](https://github.com/mperham/sidekiq.cr/wiki/Getting-Started) at Sidekiq.cr wiki for details.
