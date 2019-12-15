# Ruby On Rails Homework

## Read Ruby on Rails Guide to answer the questions below:
**[Ruby on Rails Guides](https://guides.rubyonrails.org/)**
- Apply your knowledge of Ruby on rails to answer these questions.

## Questions
1. What is Active Record?
is the layer of the system responsible for representing business data and logic. Active Record facilitates the creation and use of business objects whose data requires persistent storage to a database.


2. What is MVC?

MVC is Software design Architecture .

Model :  It is the application's dynamic data structure
View : Anything that the user sees on the page
Controller : The controller responds to the user input and performs interactions on the data model objects


3. What is REST-ful routing?

REST-ful provides a mapping between HTTP verbs, controller actions, and (implicitly) CRUD operations in a database .


4. What are migration files and why do we need them?

Migrations are files, which are responsible for making any changes in the database , They help you to evolve your database schema over time without a problem. They convert a Ruby code into a SQL code, so you don’t even write a single line of SQL code.

5. What does the `rails routes` do?

Rails router recognizes URLs and dispatches them to a controller's action, or to a Rack application. It can also generate paths and URLs, avoiding the need to hardcode strings in your views

6. Walk us through the setup and code for building a new rails app in Rails.

1- make a new project with the the folloing line 
rails new our new project -d mysql

2- create a database for our new project 
our new oriject db:create

3-the we start running our server 
rails s 

