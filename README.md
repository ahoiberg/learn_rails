# learn_rails
a guide to learning ruby on rails

This repository is meant to be a beginner's guide to learning how the internet works and how to make rails apps. Feel free to clone it, fork it, do whatever you want.

To use Rails, you "techinically" need to know Ruby. A great resource is learn X in Y minutes: https://learnxinyminutes.com/docs/ruby/

Start by installing Ruby and Rails: http://installrails.com/
Mac Users-start by installing homebrew. You should all know terminal by now, and Xcode isn't necessary.
Note that Rails is designed to be "convention over configuration." Everything is designed to be the same, I can't set up my Rails server different than yours, which makes it easier to understand anyone else's rails app.

The internet works through the Hyper Text Transfer Protocol, http. https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol
tl;dr you make a request to some server someplace (at google, facebook, amazon, tripadvisor, etc), and the server sends a response: either the information you want (typically a webpage), or an error message.

Within something like Rails, you have a lot of CRUD. CRUD is:
Create
Read
Update
Delete

Rails uses what is known as MVC, Model-View-Controller. Since this is a short presentation, MVC means that you view your Models (essentially your data) in Views (the webpages themselves) via Controllers. More information exists online, look it up if interested.