
# Beauty Salon website ✂️ 

This is Salon Havana, a Ruby on Rails website. A sample website for recruiters, managers and potential clients. This covers local setup, dependencies and development flow.

## Ruby version
2.5.1

## System dependencies
- Rails 5.2.4.3
- SQLite 3.32.3 (development)
- PostgreSQL 11.6 (production)
- Node.js 12.16.2

## Database initialization

```
$ bundle exec rake db:create
```

## How to run the test suite

```
$ rake db:test:prepare
$ bundle exec rspec
```

## Production Deployment instructions

Deployment is fully managed by [Heroku](https://www.heroku.com/).
After any change on the code is necessary to execute on the terminal:
```
$ git push heroku
```
- That will update the [production](https://salon-havana.herokuapp.com/) release.
