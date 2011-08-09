Vagrant Config
==============

A simple skeleton project for installing [Vagrant](http://vagrantup.com/) through [bundler](http://gembundler.com/) and [rvm](http://beginrescueend.com/).

Steps to install:

1. Install rvm: `$ bash < <(curl -s https://rvm.beginrescueend.com/install/rvm)`
2. Install ruby 1.9.2: `$ rvm install 1.9.2`
3. Create a vagrant gemset: `$ rvm gemset create vagrant`
4. Clone this repo: `$ git clone git@github.com:kapowaz/vagrant-config.git`
5. Change into the directory of your new checkout: `$ cd vagrant-config` and accept the rvm configuration after reviewing it
6. Bundle install: `$ bundle install`
7. Download the base box: `$ vagrant box add base http://files.vagrantup.com/lucid32.box`
8. Initialise: `$ vagrant init`
9. Bring the vagrant up: `$ vagrant up`