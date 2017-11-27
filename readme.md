# RESTful Routing

## Introduction
* Define REST and explain why it matters
    * REST is a mapping between HTTP routes and CRUD
    * Conventional and reliable
    * Follows a particular pattern
* List all 7 RESTful routes
    * Index - /dogs - GET - list all dogs
    * New - /dogs/new - GET - show new dog form
    * Create - /dogs - POST - create a new dog then redirect somewhere
    * Show - /dogs/:id - GET - show info about one dog
    * Edit - /dogs/:id/edit - GET - show edit form for one dog
    * Update - /dogs/:id - PUT - update a dog then redirect somewhere
    * Destroy - /dogs/:id - DELETE - delete a dog then redirect somewhere
* Show example of RESTful routing in practice

# Blog Index
* Setup the blog app
    * npm init
    * npm install express mongoose body-parser --save
    * touch app.js
    * npm install ejs --save
* Create the blog model
* Add INDEX route and tempalte
* Add simple nav bar
