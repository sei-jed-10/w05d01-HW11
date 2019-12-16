# Ruby On Rails Homework

## Read Ruby on Rails Guide to answer the questions below:
**[Ruby on Rails Guides](https://guides.rubyonrails.org/)**
- Apply your knowledge of Ruby on rails to answer these questions.

## Questions
1. What is Active Record?
Active Record, as an ORM Framework, gives us several mechanisms, the most important being the ability to:
represent models and their data
represent associations between these models
represent inheritance hierarchies through related models
validate models before they get persisted to the database
perform database operations in an object-oriented fashion
Active Record is the M in MVC - the model - which is the layer of the system responsible for representing business data and logic.
2. What is MVC?
Model-View-Controller
A Model directly manages the data in our application, and provides a representation of that data for the rest of the application to use.

A View is like it sounds - it's data that gets sent back to the client for the user to consume.

A Controller responds to user requests as they come in, and utilizes both the model and the view components to perform the desired behavior and produce a response.

3. What is REST-ful routing?
A RESTful route is a route that provides mapping between HTTP verbs (get, post, put, delete, patch) to controller CRUD actions (create, read, update, delete). Instead of relying solely on the URL to indicate what site to visit, a RESTful route also depends on the HTTP verb and the URL

4. What are migration files and why do we need them?
The migration file  will allow us to create a table with the columns we want.
migration files are kept in sequence so that we have a permanent record of all alterations to our database.


5. What does the `rails routes` do?
The Rails router recognizes URLs and dispatches them to a controller's action, or to a Rack application. It can also generate paths and URLs, avoiding the need to hardcode strings in your views.

6. Walk us through the setup and code for building a new rails app in Rails.
Ruby in rails
