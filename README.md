# Ruby On Rails Homework

## Read Ruby on Rails Guide to answer the questions below:
**[Ruby on Rails Guides](https://guides.rubyonrails.org/)**
- ++Apply your knowledge of Ruby on rails to answer these questions.++

## Questions
 1. What is Active Record?

 Active Record is the M in MVC - the model - which is the layer of the system responsible for representing business data and logic. Active Record facilitates the creation and use of business objects whose data requires persistent storage to a database. It is an implementation of the Active Record pattern which itself is a description of an Object Relational Mapping system.


 2. What is MVC?

 The Model-View-Controller (MVC) is an architectural pattern that separates an application into three main logical components: the model, the view, and the controller. Each of these components are built to handle specific development aspects of an application. MVC is one of the most frequently used industry-standard web development framework to create scalable and extensible projects.


 3. What is REST-ful routing?

 A RESTful route is a route that provides mapping between HTTP verbs (get, post, put, delete, patch) to controller CRUD actions (create, read, update, delete). Instead of relying solely on the URL to indicate what site to visit, a RESTful route also depends on the HTTP verb and the URL.


 4. What are migration files and why do we need them?

 - Migrations are files, which are responsible for making any changes in the database. They can create or drop a table, add or remove a column, modify it, add an index or rename it or do plenty of different thing. They can also contain a code which makes some changes in the existing data, for example, update it or remove records which are invalid.
 - Migrations are not only used in Rails, but you can find them in Django, Laravel or even in .NET MVC – they look pretty similar, and they have the same responsibility and goal.
 - They help you to evolve your database schema over time without a problem. They convert a Ruby code into a SQL code, so you don’t even write a single line of SQL code.


 5. What does the `rails routes` do?

 The Rails router recognizes URLs and dispatches them to a controller's action, or to a Rack application. It can also generate paths and URLs, avoiding the need to hardcode strings in your views.


 6. Walk us through the setup and code for building a new rails app in Rails.

 # Step 1 _ BUILD A NEW RAILS APP
 `rails new my_app -d mysql`
 `cd my_app`

