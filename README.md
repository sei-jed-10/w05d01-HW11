# Ruby On Rails Homework

## Read Ruby on Rails Guide to answer the questions below:
**[Ruby on Rails Guides](https://guides.rubyonrails.org/)**
- Apply your knowledge of Ruby on rails to answer these questions.

## Questions

1. What is Active Record?

   The active record is the data that have been entered in the database


2. What is MVC?

   MVC stands for Model-View-Controller
   Model: Manage data in our application and provides representation of data to other parts in  the application.

   View: Is the data that is sent to the client 

   Controller: responds to user on time and use Model and View to show the user the response.



3. What is REST-ful routing?

   REST-ful route is a route that provides mapping between HTTP verbs (get, post, put, delete, patch) to controller CRUD actions (create, read, update, delete).



4. What are migration files and why do we need them?

   migration files is the transfer of data between data storage systems, data formats or computer systems.


5. What does the `rails routes` do?

   Rail routs directs the landing page to another defined one.



6. Walk us through the setup and code for building a new rails app in Rails.

In Terminal we run the following commands:

$ rails new intro_app -d mysql
$ cd intro_app
$ cd intro_app
$ rails g model ****
$ rails db:migrate
