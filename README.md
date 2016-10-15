# learn_rails
a guide to learning ruby on rails

This repository is meant to be a beginner's guide to learning how the internet works and how to make rails apps. Feel free to clone it, fork it, do whatever you want.

To use Rails, you "techinically" need to know Ruby. A great resource is learn X in Y minutes: https://learnxinyminutes.com/docs/ruby/

Start by installing Ruby and Rails: http://installrails.com/

Mac Users-start by installing homebrew. You should all know terminal, and Xcode isn't necessary.
Note that Rails is designed to be "convention over configuration." Everything is designed to be the same, I can't set up my Rails server different than yours, which makes it easier to understand anyone else's rails app.

The internet works through the Hyper Text Transfer Protocol, http. https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol
tl;dr you make a request to some server someplace (at google, facebook, amazon, tripadvisor, etc), and the server sends a response: either the information you want (typically a webpage), or an error message.

Within something like Rails, you have a lot of CRUD. CRUD is:

Create - Read - Update - Delete

Rails uses what is known as MVC, Model - View - Controller. Since this is a short presentation, MVC means that you view your Models (essentially your data) in Views (the webpages themselves) via Controllers. More information exists online if you need more references.

Useful commands:

rails generate scaffold Game title:string

rake db:migrate

rake routes

rails console (or rails c)

game = game.create(:title => 'my_title')

Don't forget to add paths to your routes.rb file! my_game/config/routes.rb

Some useful links:

for relations like has_many, belongs_to: http://guides.rubyonrails.org/association_basics.html

migrations: http://edgeguides.rubyonrails.org/active_record_migrations.html

sass-rails gem: http://sass-lang.com/guide

Active Record: http://guides.rubyonrails.org/active_record_validations.html

Useful gems:

To install a gem, simply type gem install my_gem into command line

Authentication: https://www.digitalocean.com/community/tutorials/how-to-configure-devise-and-omniauth-for-your-rails-application

Using Google Maps: https://github.com/apneadiving/Google-Maps-for-Rails

Pagination: https://github.com/mislav/will_paginate

Stripe: https://github.com/stripe/stripe-ruby

More useful gems exist, simply google what you want to do!

Many thanks to Salman Ansari and to iXperience for teaching me Ruby on Rails.
