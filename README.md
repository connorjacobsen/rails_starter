RailsStarter
============

RailsStarter is a Rails application template with most of the setup you're sick of doing for every project already done, just fork it, set the application name in one place and you're on your way.

This is my own Rails setup, so I do not care if you prefer HAML to Slim or LESS to SASS, I don't use those tools so I didn't include them here.

## Current Defaults
- Ruby version: 2.1.2
- Rails version: 4.1.1
- Templating language: [slim](https://slim-lang.com)
- Stylesheet language: SASS
- Development database: sqlite3
- Production database: Postgresql
- Server: Puma

## Other Dependencies
- Nodejs for the JavaScript runtime.
- Yes, you must have Rails installed on your machine...

## Usage

Getting started with RailsStarter is quick and painless. Either clone the repo to your own machine or create your own fork of the project.

If you wish to give the application a custom name, simply make one little change from:

```ruby
# config/application.rb
module RailsStarter
end
```

To:
```ruby
# config/application.rb
module YourApplicationNameHere
end
```

After running `bundle install` and `rails s` you should be able to navigate to `localhost:3000/` and see the *Hello, World!* message.

*Note: You may also want to tweak the database.yml as you see fit.*
