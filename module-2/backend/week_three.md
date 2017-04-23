## Week Three Recap

### Instructions
Fork this repository. Be sure to pull the latest changes to your local repo. Answer the questions to the best of your ability.

Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR with a reflection in the comments about how this exercise went for you.

### Questions

1. What is the entry at the command line to create a new rails app?
>* Rails generate new app_name
2. What do Models generally inherit from in rails?
>* ActiveRecord::Base
3. What do Controllers generally inherit from in a rails project?
>* For rails < 5 Active Record, for rails 5, ApplicationRecord
4. How would I create a route if I wanted to see a specific horse in my routes fitle assuming I'm sticking to standard conventions and that I didn't want other CRUD functionality?
>* resources :horses, only: [:show]
5. What rake task is useful when looking at routes, and what information does it give you?
>* rake routes
6. What is an example of a route helper? When would you use them?
>* "/dashboard", to: "session#index" as: "dashboard"
>* use them when you manually want to create a path with a specific url
7. What's the difference between what `_url` and `_path` return when combined with a routes prefix?
>* "/dashboard" would be the url
>* dashboard_path, would be the path
8. What are strong params and why are the necessary?
>* They limit what params you can pass through to only what you want so no other changes are made
9. What role does `form_for` play in helping us create our forms?
>* It allows us to choose what object we're creating a form for
10. How does `form_for` know where to submit the user's input?
>* The controller
11. Create a form using a `form_for` helper to create a new `Horse`. 
<%= form_for @horse do |f| %>
<%= f.label :name %>
<%= f.text_field :name %>
<% end %>
12. Why do we want to validate our models?
>* to make sure we are filling out our forms correctly.
