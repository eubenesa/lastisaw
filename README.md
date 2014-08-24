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

## Getting up and running

1. `bundle install`
2. `bundle exec rake db:setup`
3. `bundle exec shotgun -p 3000 -o 0.0.0.0`
4. Visit `http://localhost:3000/` in your browser.

## Debugging

Ideally, you should have at least 3 tabs open in your CLI for debugging. Run these commands from the repository's root directory:  
1. `bundle exec shotgun -p 3000 -o 0.0.0.0`  
2. `bundle exec pry -r './config/environment.rb'`  
3. `sqlite3 db/db.sqlite3`
