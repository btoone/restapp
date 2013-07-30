Overview
========

This app serves as a simple RESTful back-end for apps with heavy javascript front-ends. It currently
supports CRUD actions on a `cars` resource

This app is hosted on Heroku at http://polar-falls-1728.herokuapp.com/

Here is an [JSFiddle](http://jsfiddle.net/caspyin/LgApT/) that is an example of an AngularJS app
making use of this app.


CORS and REST
=============

In order to make this back-end work for a standalone JavaScript app I had to add the `rack-cors` gem
and configure it in the `config/application.rb`.

I then used simple scaffolding to create the Car resource. This app will respond to both `html` and
`json`.

