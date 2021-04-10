# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version: 3.0.1

* System dependencies: see gemfile

* Configuration

* Database creation
removed brew install 
install with https://postgresapp.com/
export PATH=/Applications/Postgres.app/Contents/Versions/latest/bin/:$PATH
  Connection URL 	postgresql://localhost
  Port 5432
  User postgres


* Database initialization for ruby app
used the driver provided by the Rubymine IDE
  and the console and other tools
  anyway pgadmin does not work
 on mac, open console:
  command:
  psql
  postgres=# createdb mydb

  to list all tables
  postgres-# \l
TODO => set password in database.yml using IDE tools 

db created in IDE can be seen in Mac console => great stuff

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
