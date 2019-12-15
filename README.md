# Ruby On Rails Homework

## Read Ruby on Rails Guide to answer the questions below:
**[Ruby on Rails Guides](https://guides.rubyonrails.org/)**
- Apply your knowledge of Ruby on rails to answer these questions.

## Questions
1. What is Active Record?
Active Record, as an ORM (Object Relation Mapping) Framework.
Active Record is the M in MVC - the model - which is the layer of the system responsible for representing business data and logic.
Active Record will convert our SQL into JSON

2. What is MVC?
Model-View-Controller (MVC) architecture pattern. This pattern involves making three core types of components, each responsible for a different part of the server's functionality.

A Model directly manages the data in our application, and provides a representation of that data for the rest of the application to use.

A View is like it sounds - it's data that gets sent back to the client for the user to consume.

A Controller responds to user requests as they come in, and utilizes both the model and the view components to perform the desired behavior and produce a response.

3. What is REST-ful routing?
Representational state transfer
A RESTful route is a route that provides mapping between HTTP verbs (get, post, put, delete, patch) to controller CRUD actions (create, read, update, delete). 

4. What are migration files and why do we need them?
Migrations are a convenient way for you to alter your database in a structured and organized manner.

5. What does the `rails routes` do?
Routes indicate to the server which controllers should be triggered (and how) by which kinds of requests.

6. Walk us through the setup and code for building a new rails app in Rails.
Run the git bash and write these commands:
1-Installing Rails:
command: gem install rails
2-Run rails server:
command: rails s
3- build an app build an app called intro_app:
command: rails new intro_app -d mysql