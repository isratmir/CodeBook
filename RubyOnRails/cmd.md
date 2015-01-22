#CMD commands

###Command Line Basics

* rails console
* rails server
* rake
* rails generate
* rails dbconsole
* rails new app_name

[Detailed description]: http://guides.rubyonrails.org/command_line.html

> All commands can run with -h or --help to list more information.

####rails new

The first thing we'll want to do is create a new Rails application by running the rails new command after installing Rails.

```
$ rails new commandsapp
     create
     create  README.rdoc
     create  Rakefile
     create  config.ru
     create  .gitignore
     create  Gemfile
     create  app
     ...
     create  tmp/cache
     ...
        run  bundle install
```

####rails server

The rails server command launches a small web server named WEBrick which comes bundled with Ruby. You'll use this any time you want to access your application through a web browser.

> You can also use the alias "s" to start the server: rails s.

####rails generate

The rails generate command uses templates to create a whole lot of things. Running rails generate by itself gives a list of available generators:

> You can also use the alias "g" to invoke the generator command: rails g.

```
$ bin/rails generate
Usage: rails generate GENERATOR [args] [options]
 
...
...
 
Please choose a generator below.
 
Rails:
  assets
  controller
  generator
  ...
  ...
```

####rails console

The console command lets you interact with your Rails application from the command line. On the underside, rails console uses IRB, so if you've ever used it, you'll be right at home. This is useful for testing out quick ideas with code and changing data server-side without touching the website.

> You can also use the alias "c" to invoke the console: rails c.

