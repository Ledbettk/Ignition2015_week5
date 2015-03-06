#### Deliverables for week 5 Rails MVC
##### Odin Project Routing Guide Questions:
- What is the "Root" route?
  the most important route, it tells the server where a user should be sent when they first visit your website's URL.

- What are the seven RESTful routes for a resource?
  GET all the posts
  GET just one specific post
  GET the page that lets you create a new post
  POST the data you just filled out for a new post back to the server so it can create that post
  GET the page that lets you edit an existing post
  PUT the data you just filled out to edit the post back to the server so it can actually perform the update
  DELETE one specific post by sending a delete request to the server 

- Which RESTful routes share the same URL but use different verbs?
GET "/posts/:id"
Put "/posts/:id"
Delete "/posts/:id"

- How do you specify an ID or other variable in a route?
you use a colon : to tell rails that it needs to save info as the ID in the params hash

- How can you easily write all seven RESTful routes in Rails?
  in config/routes.rb you put:
resources :posts

- What is the Rails helper method that creates the HTML for links?
  These methods end with _path and _url such as link_to "Edit this post", edit_post_path(3)

##### Odin Project Views Guide Questions:
- What is a layout?
- What's the difference between a "view template" and a "layout"?
- What is a "Preprocessor"?
- Why are preprocessors useful?
- How do you make sure a preprocessor runs on your file?
- What's the outputted filetype of a preprocessed *.html.erb file? What about a *.css.scss file?
- What is the difference between the <%= and <% tags?
- What is a view partial?
- How do you insert a partial into your view?
- How can you tell that a view file is a partial?
- How do you pass a local variable to a partial?
- What's the magical Rails shortcut for rendering a User? A bunch of Users?
- What are asset tags and why are they used?

##### Link to Odin Project Basic Routes, Views and Controllers repo: [my odin repo](<linkhere>)
##### Link to Hartl's Rails Tutorial Chapter 5 repo: [my hartl's repo](<linkhere>)
