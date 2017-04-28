## Week Four Recap

### Instructions
Fork this repository. Answer the questions to the best of your ability.

Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR with a reflection in the comments about how this exercise went for you.

### Questions

* What is a cookie?
>* Hold info of specific computers that visit your site.

* What’s the difference between a session and a cookie?
>* session data is stored on the server
>* cookies store data in the visitor's browser

* What’s a flash and when do you want to use flashes?
>* Flashes are messages that you want to send to users to provide instant info/feedback

* Why do people say “HTTP is stateless”?
>* means that the connection between the browser and the server is lost

* What’s authentication? Explain.
>* making sure you are who you say you are. making you log in

* What’s the difference between authentication and authorization?
>* authentication ^
>* authorization is what youre allowed to do on a site ie normal user or admin

* What’s a before filter?
>* before any action it will check that method, allowing you to see if someoene is an admin first.

* How do we keep track of a user once they’ve logged in?
>* cookies

* When do you want to namespace a resource? When do you want to nest a resource? What's the differences between those two approaches?
>* when we're using every element of a resource we'll namespace
>* we nest resources when you want to restrict where it goes ,or if it belongs to the one it's nested in

* At a high level, what tools can you use to implement authorization? How would you use them?
>* add an admin class, check to make sure someoen is an admin before they log in

* What's an enum, and what advantages does it offer? What data type needs to be in your database to use an enum? Where do you declare an enum?
>* a data type consisting of a set of named values
>* an enum value you ensure that no code ever enters incorrect values for that column

* What are some strategies you can use to keep your views DRY?
>* leaving the extensibility of adding new knowledge variables in one place.
