# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

   `ruby 2.4.+`
   
* System dependencies
  ```
  rails 5.1
  puma
  foreman
  npm
  yarn
  ```

* Configuration
  Create server run file on bin folder
  
  ```sh
  #!/bin/bash -i
  bundle install
  bundle exec foreman start -f Procfile.dev
  ```

  Create `Procfile` with
 
  ```
  web: bundle exec puma -p $PORT%
  ```

* Database creation

  `rails db:setup`

* Run application

   `bin/server`

  Access base from http://0.0.0.0:8080/ or http://localhost:8080
