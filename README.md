# Ruby On Rails Homework

## Read Ruby on Rails Guide to answer the questions below:
**[Ruby on Rails Guides](https://guides.rubyonrails.org/)**
- Apply your knowledge of Ruby on rails to answer these questions.

## Questions
1. What is Active Record?
An Active Record is the Model in a Model-View-Controller (MVC) architecture pattern MVC. a model is the layer of the system responsible for representing business data and logic.

2. What is MVC?
Model-View-Controller (MVC) is an architecture pattern that involves making three types of components, each responsible for a different part of the server's functionality: a model: represents the data, view (or views): HTML page(s) and a controller: the logic between the model and the view.

3. What is REST-ful routing?
Is the mapping between HTTP commands such as GET and POST to controller'S CRUD actions (create, read, update, delete).

4. What are migration files and why do we need them?
Is a small program required by ruby in order to change any database fields.

5. What does the `rails routes` do?
They work as dispatchers/directing modules that read browser URLs and dispatch them to the controller based on the actions requested.

6. Walk us through the setup and code for building a new rails app in Rails.
  
  Using Git Bash:
  1- CD into the folder where we want to build our app.
  
  2- write the following command :
 ```
 rails new app_name -d mysql
```
where app_name should be replaced by the name we want for our appliction.
3- Start the rails server by typing:
 ```
 rails s
```
  
