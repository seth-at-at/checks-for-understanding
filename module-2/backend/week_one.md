## Week One - Module 2 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week (which is a TON!). 

Note: When you're done, submit a PR. 

1. List the five common HTTP verbs and what the purpose is of each verb.
 * GET : Read
 * PUT : Update replace
 * POST : Create
 * DELETE : delete
 * PATCH : Update and modify
2. What is Sinatra?
* source software web application library and domain-specific language 
4. What is MVC?
* Model View Controller : framework of how to build a user interface for an application. 
5. Why do we follow conventions when creating our actions/path names in our Sinatra routes?
* Readability for future devs that see your code
6. What types of variables are accessible in our view templates without explicitly passing them?
* Local Variables
7. Given the following block of code, how would I pass an instance variable `count` with a value of `1` to my `index.erb` template?
  
  ```ruby
  get '/horses' do
    @count = 1
    @name = "Mr. Ed"
    erb :index
  end
  ```

8. In the same code block, how would I pass a local variable `name` with a value of `Mr. Ed` to the view?
9. What's the purpose of ERB?
* Embed dynamic ruby content into html 
10. Why do I need a development AND test database?
* Test : database clears data so it's not populated in future uses
* Development : populates with given data as well but allows you to work with the database in the views while you are developing the application. 
11. What's responsive design?
* Elements resize depending on the screen size
12. What is CRUD and why is it important?
* Create 
* Read
* Update
* Delete
* Basic funtionality web apps should have
13. What does HTTP stand for? 
* Hypertext Transfer Protocol
14. What are the two ways to interpolate Ruby in an ERB view template? What's the difference between these two ways?
```ruby
  <%= %>
  <% %>
```
15. What's an ORM?
* Object Relational Mapping
* Connects programming language to a database
16. What's the most commonly used ORM in ruby (Sinatra & Rails)?
* ActiveRecord
17. Let's say we have an application with restaurants. There are seven verb + path combinations necessary to provide full CRUD functionality for our restaurant application. List each of the seven combinations, and explain what each is for.
* GET '/restaurants' - all restaurants
* GET '/restaurants/new' - form to create new restaurant
* POST '/restaurants' - post list of new restaurant list
* GET '/restaurants/:id' - specific restaurant list
* GET '/restaurants/:id/edit' - edit specific restaurant
* PUT '/restaurants/:id' - updates specific restaurant
* DELETE '/restaurants/:id' - delete the specific restaurant
18. What's a migration? 
* creates/updates the database schema 
19. When you create a migration, does it automatically modify your database?
* no, you must rake db:migrate
20. How does a model relate to a database?
* Interacts with the data from the database
21. What's the difference between agile workflow and waterfall method?
* Agile: Plan one thing at a time, test it, and build from the test.
* Waterfall: Plan whole thing from the beginning, testing at the end.
22. What is the difference between `#new` and `#create`?
* Create : makes a new object and saves it
* New : creates a new object but does not save it
