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

The layout had the basic tags you need in all webpages and some other code that loads up the javascript and css files your webpage will need. Anything that is needed across all your webpages go into the layout.

- What's the difference between a "view template" and a "layout"?

The layout is basically just a shell around the individual page, and the view template has the HTML that you want displayed on your pages.

- What is a "Preprocessor"?
 The <%= and %> tags. This is Embedded Ruby (ERB). It's a special way of executing ruby code inside your HTML

- Why are preprocessors useful?
HTML creates static outputs, but with preprocessors like ERB you can make your content dynamic.

- How do you make sure a preprocessor runs on your file?

  Rails knows you want to preprocess the file because it has the extension .html.erb.

- What's the outputted filetype of a preprocessed *.html.erb file? What about a *.css.scss file?


- What is the difference between the <%= and <% tags?

The difference between <% and <%= is that the <%= version actually displays whatever is returned inside the ERB tags. If you use <%, it will execute the code but it will not actually display anything in the HTML template

- What is a view partial?
- How do you insert a partial into your view?
- How can you tell that a view file is a partial?
- How do you pass a local variable to a partial?
- What's the magical Rails shortcut for rendering a User? A bunch of Users?
- What are asset tags and why are they used?

##### Link to Odin Project Basic Routes, Views and Controllers repo:
 https://github.com/Ledbettk/odin-mvc-project

 https://odinmvc-project-ledbettk.c9.io
##### Link to Hartl's Rails Tutorial Chapter 5 repo:
 https://github.com/Ledbettk/ruby-rails-tut2

 https://ruby-rails-tut2-ledbettk.c9.io

 https://kelsey-rails-app.herokuapp.com/
