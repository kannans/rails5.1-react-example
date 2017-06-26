# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version
  2.4 +
* System dependencies
  rails 5.1
  puma
  foreman
  npm
  yarn

* Configuration
  create server run file on bin folder
  ```sh
  #!/bin/bash -i
  bundle install
  bundle exec foreman start -f Procfile.dev
  ```

  create Procfile with `
  `web: bundle exec puma -p $PORT%`

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
