# README

## DESCRIPTION
Welcome to Speakeasy! This is a [Turing School of Software and Design](https://turing.io/) project that facilitates and adds fun to remote team workflow. The project is based on requirements found [here](https://backend.turing.io/module3/projects/terrificus).

The project revolves around sending deployment webhooks and Slack commands to a Rails database, and then retreiving information from that database via Amazon Skills and Alexa devices or Slack.

Users can hear Github commit messages or branch names involved with merges, as well as add shoutouts to their teams.


## REQUIREMENTS
Ruby version
* [Ruby 2.4.1](https://www.ruby-lang.org/en/downloads/)
* [Ruby 2.4.1](https://rubygems.org/gems/rails/versions/5.2.3)
  
## System dependencies
* gem 'figaro'
* gem 'faraday'
* gem 'rspec-rails'
  
Database initialization
* rails db:{drop,create,migrate,seed}
  
How to run the test suite
* `$ rspec`
  
Deployment instructions
* Start 3 separate web apps and buy an Alexa. Go to the Alexa Skill Store and download our skill. Use Alexa skill to interact with slack and get your commit messages to your Alexa
  
**Dummy repo for merges:**
* Heroku: https://quiet-basin-56396.herokuapp.com/
* Github: https://github.com/james-cape/dummy_speakeasy

**Flask webhook api passthrough app:**
* Heroku: https://shielded-mountain-70953.herokuapp.com
* Github: https://github.com/james-cape/speakeasy_webhook_passthrough

**Rails app:**
* Heroku: https://arrogant-loon-34609.herokuapp.com/
* Github: https://github.com/davehardy632/SpeakEasy

![Speakeasy flow diagram](https://arrogant-loon-34609.herokuapp.com/assets/welcome/flow.png)
