# README

 A starter application for rails 5.1 with ReactJS

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
  Create a `server` file at `bin` folder from rails directory and with following code
  
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
