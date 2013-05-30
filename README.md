Overview
========

This app serves as a simple RESTful back-end for AngularJS example apps. Specifically this fiddle
http://jsfiddle.net/caspyin/LgApT/

This app is hosted on Heroku at http://polar-falls-1728.herokuapp.com/

AngularJS and REST
==================

In order to make this back-end work for a standalone Angular app I had to add the `rack-cors` gem
and configure it in the `config/application.rb`.

I then used simple scaffolding to create the Car resource. This app will responde to both `html` and
`json`.

