#RESTful Routing

##Introduction
* Define REST and explain WHY it matters
* List all 7 RESTful routes
* Show example of RESTful routing in practice

REST - a mapping between HTTP routes and CRUD

BLOG

CREATE
READ    /allBlogs
UPDATE  /updateBlog/:id
DESTROY /destroyBlog/:id

index   /dogs           GET         List all dogs
new     /dogs/new       GET         Show new dog form
create  /dogs           POST        Create a new dog, then redirect
show    /dogs/:id       GET         Show info about one dog
edit    /dogs/:id/edit  GET         Show edit form for one dog
update  /dogs/:id       PUT         Update a particular, then redirect
destroy /dogs/:id       DELETE      Delete a particular dog, then redirect

#Blog Index
* Setup the Blog App
* Create the Blog model
* Add INDEX route and template
* Add Simple Nav Bar