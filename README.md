# Ruby On Rails Homework

## Read Ruby on Rails Guide to answer the questions below:
**[Ruby on Rails Guides](https://guides.rubyonrails.org/)**
- Apply your knowledge of Ruby on rails to answer these questions.

## Questions
1. What is Active Record?

Active Record is the M in MVC - the model - which is the layer of the system responsible for representing business data and logic. Active Record facilitates the creation and use of business objects whose data requires persistent storage to a database. It is an implementation of the Active Record pattern which itself is a description of an Object Relational Mapping system.

2. What is MVC?

Model–view–controller, is a software design pattern commonly used for developing user interfaces which divides the related program logic into three interconnected elements. This is done to separate internal representations of information from the ways information is presented to and accepted from the user. Following the MVC architectural pattern decouples these major components allowing for code reuse and parallel development.

3. What is REST-ful routing?

REST is an architectural style, that is used in Rails by default. As a Rails developer, RESTful design helps you to create default routes by using resources keyword followed by the controller name in the the routes.rb file

4. What are migration files and why do we need them?

Migrations are a convenient way to alter your database schema over time in a consistent and easy way. They use a Ruby DSL so that you don't have to write SQL by hand, allowing your schema and changes to be database independent.
You can think of each migration as being a new 'version' of the database. A schema starts off with nothing in it, and each migration modifies it to add or remove tables, columns, or entries. Active Record knows how to update your schema along this timeline, bringing it from whatever point it is in the history to the latest version. Active Record will also update your db/schema.rb file to match the up-to-date structure of your database.

5. What does the `rails routes` do?

The Rails router recognizes URLs and dispatches them to a controller's action, or to a Rack application. It can also generate paths and URLs, avoiding the need to hardcode strings in your views.

6. Walk us through the setup and code for building a new rails app in Rails.
In command:
- rails new intro_app -d mysql
- cd intro_app
_____________
- CREATE DATABASE
rails db:create
-  run server: rails s

