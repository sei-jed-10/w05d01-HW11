# Ruby On Rails Homework

## Read Ruby on Rails Guide to answer the questions below:
**[Ruby on Rails Guides](https://guides.rubyonrails.org/)**
- Apply your knowledge of Ruby on rails to answer these questions.

## Questions
1. What is Active Record?
Active Record is the M in MVC - the model - which is the layer of the system responsible for representing business data and logic.

2. What is MVC?
Model-View-Controller (MVC) architecture pattern.
A Model directly manages the data in our application, and provides a representation of that data for the rest of the application to use.

A View is like it sounds - it's data that gets sent back to the client for the user to consume.

A Controller responds to user requests as they come in, and utilizes both the model and the view components to perform the desired behavior and produce a response.

3. What is REST-ful routing?
A RESTful route is a route that provides mapping between HTTP verbs (get, post, put, delete, patch) to controller CRUD actions (create, read, update, delete). Instead of relying solely on the URL to indicate what site to visit, a RESTful route also depends on the HTTP verb and the URL.

4. What are migration files and why do we need them?
We create our database tables and give them columns through Migrations. In SQL this is a table that has columns. We are going to make a ToDo app with very simple data.

5. What does the `rails routes` do?
The Rails router recognizes URLs and dispatches them to a controller's action, or to a Rack application. It can also generate paths and URLs, avoiding the need to hardcode strings in your views.

6. Walk us through the setup and code for building a new rails app in Rails.
rails new intro_app -d mysql
rails new will make a new project directory and populate it with folders and files
The name of our app is intro_app.
With the -d flag we specify which type of database to use. In our case, we use mysql
