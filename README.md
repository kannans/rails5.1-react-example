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

  Create `Procfile.dev` for local development server configuration
  ```sh
   web: bundle exec rails s
   # watcher: ./bin/webpack-watcher
   webpacker: ./bin/webpack-dev-serve
  ```

  For heroku production Create `Procfile` with
 
  ```
  web: bundle exec puma -p $PORT%
  ```

* Database creation

  `rails db:create && rails db:migrate` 
  
   or 
  
  `rails db:setup`

* Run application

   `bin/server`

  Access base from http://localhost:5000
