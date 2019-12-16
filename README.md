# Ruby On Rails Homework

## Read Ruby on Rails Guide to answer the questions below:
**[Ruby on Rails Guides](https://guides.rubyonrails.org/)**
- Apply your knowledge of Ruby on rails to answer these questions.

## Questions
1. What is Active Record?
Active recored is in the MVC the model which is the layer of the system  responsible for representing business data and logic its facilitates the creation and use of business objects whose data requires persistent storge to database.

2. What is MVC?
its stand for model ,view ,and controller the model contains data ,state and all business logic.  
the view its displayed the data to the users
the controller Receive events from the outside world , Interact with the model ,and displays the appropriate view to the user

3. What is REST-ful routing?
A RESTful route is a route that provides mapping between HTTP verbs (get, post, put, delete, patch) to controller CRUD actions (create, read, update, delete). Instead of relying solely on the URL to indicate what site to visit, a RESTful route also depends on the HTTP verb and the URL.


4. What are migration files and why do we need them?
Rails Migration allows you to use Ruby to define changes to your database schema, making it possible to use a version control system to keep things synchronized with the actual code. Teams of developers − If one person makes a schema change, the other developers just need to update, and run "rake migrate".

5. What does the `rails routes` do?
The Rails router recognizes URLs and dispatches them to a controller's action, or to a Rack application. It can also generate paths and URLs, avoiding the need to hardcode strings in your views.



6. Walk us through the setup and code for building a new rails app in Rails

Setup an new rails app
first we need to use this command

rails new intro_app -d mysql

cd intro_app
code .

than creat database useing this command
rails db:create

We can check that the database by going into MySQL Workbench

Now we can run rails s from the command line to start our server. Go to localhost:3000 in the browser and you should see this:
