# Ruby On Rails Homework

## Read Ruby on Rails Guide to answer the questions below:
**[Ruby on Rails Guides](https://guides.rubyonrails.org/)**
- Apply your knowledge of Ruby on rails to answer these questions.

## Questions
1. What is Active Record?
Is the m in MVCAn object-Relation Maping(ORM) that will convert Sql into JSON and insted you can write Ruby query:Represent models and data.Represent associations between these modelsrepresent inheritance hierarchies through related modelsvalidate models before they get persisted to the databaseperform database operations in an OOP.

2. What is MVC?
Model-View-Controller

3. What is REST-ful routing?
 Representational state transfer,is a software architectural style used to create web services such as standard HTTP method GET, POST , PUT , PATCH , DELETE  


4. What are migration files and why do we need them?
Is a small program that create and change any database fields

5. What does the `rails routes` do?
Resorceful route provdie maping between HTTP and URLs

6. Walk us through the setup and code for building a new rails app in Rails.

* gem install rails 
* rails new intro_app -d mysql
//create database
* rails db:create
//create a root route
get "about", to: "application#aboutMe"
