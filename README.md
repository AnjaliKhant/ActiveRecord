# README

ActiveRecord is a gem that is part of Ruby on Rails. It is the ORM, i.e. the library that maps our objects to tables. In other words, it is the Ruby library that allows us to use Ruby classes in order to access our data stored in an RDBMS, like MySQL or PostgreSQL.

Things you may want to cover:

* Ruby version = 

* Install gem

      gem 'activerecord'
      gem 'standalone_migrations'

* Configuration

* Database creation

  Decide your database i have used postgresql database.
      gem pg
      
  Create your databse 
      bundle exec rake db:create

* Database initialization
      
  Create first migration
      bundle exec rake db:new_migration[table_name]   

* How to run the test suite

  for testing run main.rb
     bundle exec ruby app/main.rb 


