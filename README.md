# microwave-rails
Microwave MVC provides basic, cross-platform-compatible templates for different tech stacks so you can quickly get started with web development.

#### What you get out of this Microwave:
* Ruby 2.2 & Rails 4.2
* Postgres
* Puma Webserver
* Ubuntu 14.04 Vagrant box
* provisioned using Chef / Test Kitchen / Berkshelf
* optimized for deployment to Heroku

#### Dependencies:
* Virtualbox
* Vagrant
* ChefDK

## 1-Minute Ruby on Rails
    $ vagrant plugin install vagrant-cachier
    $ vagrant plugin install vagrant-berkshelf
    $ cd rails-app
    $ vagrant up
    $ vagrant ssh
    $ cd microwave-workspace
    $ bundle install
    $ bundle exec rake db:create
    $ bundle exec puma
    * See it ready to go at http://localhost:5000!
