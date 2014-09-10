# [Last I Saw](http://lastisaw.herokuapp.com/)

Lighthouse Labs W4 project  
Brought to you by Eubene Sa and Sunil Unka

## The stack

* Ruby
* Sinatra
* Instagram API
* Bootstrap/HTML/CSS
* SQLite -> PostgreSQL
* Tiny, tiny bit of JavaScript/jQuery  

## Getting it up and running locally

1. `git clone git@github.com:eubenesa/lastisaw.git`
2. `bundle install`
3. `bundle exec rake db:setup`
4. `bundle exec shotgun -p 3000 -o 0.0.0.0`
5. Visit `http://localhost:3000/` in Chrome.

## Debugging

Ideally, you should have at least 2 additional tabs open in your Terminal for debugging. Run the following commands from the project's root directory:  
  
1. `bundle exec pry -r './config/environment.rb'`  
2. `sqlite3 db/db.sqlite3`  

## [Project management](https://trello.com/b/upwrPWzj/last-i-saw)
