# Ruby On Rails Homework

## Read Ruby on Rails Guide to answer the questions below:
**[Ruby on Rails Guides](https://guides.rubyonrails.org/)**
- Apply your knowledge of Ruby on rails to answer these questions.

## Questions
1. What is Active Record?
	 Active Record is the Object/Relational Mapping (ORM) layer supplied with Rails. It closely follows the standard ORM model, which is as follows :
		- tables map to classes,
		- rows map to objects and
		- columns map to object attributes.
	 Rails Active Records provide an interface and binding between the tables in a relational database and the Ruby program code that manipulates database records.
	---------------------------
2. What is MVC?
	Model View Controller is an architectural pattern that separates an application into three main logical components: the model, the view, and the controller. Each of these components are built to handle specific development aspects of an application. MVC is one of the most frequently used industry-standard web development framework to create scalable and extensible projects.
	---------------------------
3. What is REST-ful routing?
	 Representational State Transfer (REST), is an architectural style and an approach to communications between services that are online & often used in Web Services / Web API development.
	---------------------------
4. What are migration files and why do we need them?
	Migrations are a convenient way to alter your database schema over time in a consistent and easy way. They use a Ruby DSL so that you don't have to write SQL by hand, allowing your schema and changes to be database independent.
	Migrations are stored as files in the db/migrate directory, one for each migration class. The name of the file is of the form YYYYMMDDHHMMSS_migration_class_name.rb, that is to say a UTC timestamp identifying the migration followed by an underscore followed by the name of the migration. The name of the migration class (CamelCased version) should match the latter part of the file name.Rails uses this timestamp to determine which migration should be run and in what order.
5. What does the `rails routes` do?
	routes our application to our html page
	----------------------------
6. Walk us through the setup and code for building a new rails app in Rails.
	- rails s to run the server
	- rails new app_name -d database type
	- cd app_name
	- code.
	- config > database.yml > set the data base password > controllers > views > creat application folder > creat our html file embded with ruby > config > routes.rb > modify modify it to GET our html page in the application folder
