# README

# Crypto-Wallet #
Thanks for checking out my humble app. If you have a suggestion
that would make this better, please fork the repo and create a pull request.

Thanks again! 


## Getting started ##

Crypto-Wallet is a simple way to calculate your cryptocoin savings! 
It is a Rails 2.7.2 application so the first thing to do to get started is to install its dependencies:
For persistence the app uses postgreSQL. So libpq-dev lib is expected to be installed on server machine. This can be done easily in Ubuntu like this:

    $ sudo apt-get install libpq-dev
    
* Install yarn, node 
    
*Yarn*

    $ curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
    
    $ echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
    
    $ sudo apt update && sudo apt install yarn


* Install all necessary gems:

    $ gem install rails
  
    $ gem install bundler
    
* System dependencies

   $ bundle install
   
   $ yarn install
 


* Configuration

* Database: Postgres SQL

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
