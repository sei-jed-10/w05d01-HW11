# Ruby On Rails Homework

## Read Ruby on Rails Guide to answer the questions below:
**[Ruby on Rails Guides](https://guides.rubyonrails.org/)**
- Apply your knowledge of Ruby on rails to answer these questions.

## Questions
1. What is Active Record?
2. What is MVC?
3. What is REST-ful routing?
4. What are migration files and why do we need them?
5. What does the `rails routes` do?
6. Walk us through the setup and code for building a new rails app in Rails.

## Solution 
1. What is Active Record?
Active Record it's rails implementation of active record pattern. It allows us to retrieve and manipulate data as objects, not as static rows of data. 


2. What is MVC?
The M stands for model (Handles Data)
The V stands for View (Handles presentation)
The C stands for Controller (Handles Decisions)

The model is our objects it's the object oriented approach to design and it actually encapsulates the data in our database as well we can treat those as objects.

The view is the presentation layer it's what the user sees and interacts with the webpages the HTML, CSS and JavaScript.

The controller is going to process and respond to events such as user actions and it's going to invoke changes to the model in the view based on that it's going to make decisions for us and control what happens.


3. What is REST-ful routing?
REST stands for representational state transfer. Communication system that rests uses the HTTP protocol.
One of the issues with HTTP is that it's stateless which means that when you navigate from one page to another page, HTTP doesn't retain any of the information between the pages. It means that developers need to implement code to let applications know how to act. 

REST-ful routing is the definition of simplicity, essentially REST is a naming structure that encompasses every action that users and applications need to make. So, it maps HTTP VERBS + URL to a specific action in the controller.


4. What are migration files and why do we need them?
migration file does generates those tables in the database schema. so these tables are needed to actually record any data that the user post on your site that you want to save from the user.


5. What does the rails routes do?
The routes is the endpoint that is put in the address bar of a browser. So, in the address bar for example, google.com everything after the slash is the only way that you interact with the application and most of the time the user doesn't actually type that in the address, they're clicking on a link or they're clicking on a button and thats just going to another endpoint so this is the only way the user can communicates with the app. 
the route is made up of a unique pairing of the method, also known like the HTTP verb and the endpoint itself which is the structure of everything after that slash. 


6. Walk us through the setup and code for building a new rails app in Rails.
1- Installing Rails with "gem install rails" command.
2- checking that rails server is installed properly with "rails s" command.
3-  we added the root password under config > database.yml
4- go to the created App folder location on the terminal and run "rails new intro_app -d mysql" command line to define the database 
5- creates mysql database with "rails db:create" command
6- start up the web server


