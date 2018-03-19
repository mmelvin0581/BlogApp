#RESTful Routing

##Introduction
* Define REST and explain WHY it matters
* List all 7 RESTful routes
* Show example of RESTful routing in practice

REST - a mapping between HTTP routes and CRUD

BLOG

<ul>
    <li>CREATE</li>
    <li>READ    /allBlogs</li>
    <li>UPDATE  /updateBlog/:id</li>
    <li>DESTROY /destroyBlog/:id</li>
</ul>

<h4>Example REST Routes</h4>

<table style="width: 100%;">
    <tr>
        <th>Name</th>
        <th>Path</th>
        <th>HTTP Verb</th>
        <th>Purpose</th>
    <tr>
        <td>INDEX</td>
        <td>/dogs</td>
        <td>GET</td>
        <td>List all dogs</td>
    </tr>
    <tr>
        <td>NEW</td>
        <td>/dogs/new</td>
        <td>GET</td>
        <td>Show new dog form</td>
    </tr>
    <tr>
        <td>CREATE</td>
        <td>/dogs</td>
        <td>POST</td>
        <td>Create a new dog, then redirect</td>
    </tr>
    <tr>
        <td>SHOW</td>
        <td>/dogs/:id</td>
        <td>GET</td>
        <td>Show info about one dog</td>
    </tr>       
    <tr>
        <td>EDIT</td>
        <td>/dogs/:id/edit</td>
        <td>GET</td>
        <td>Show edit form for one dog</td>
    </tr>
    <tr>
        <td>UPDATE</td>
        <td>/dogs/:id</td>
        <td>PUT</td>
        <td>Update a particular, then redirect</td>
    </tr>
    <tr>
        <td>DESTROY</td>
        <td>/dogs/:id</td>
        <td>DELETE</td>
        <td>Delete a particular dog, then redirect</td>
    </tr>
</table>

#Blog Index

* Setup the Blog App
* Create the Blog model
* Add INDEX route and template
* Add Simple Nav Bar

#Basic Layout
* Add Header and Footer partials
* Include SemanticUI
* Add Simple Nav

#Putting the C in CRUD
* Add NEW route
* Add NEW template
* Add CREATE route
* Add CREATE template

#SHOWtime
* Add SHOW route
* Add SHOW template
* Add links to show page
* Style show template

#Edit/Update
* Add EDIT route
* Add EDIT form
* Add UPDATE route
* Add UPDATE form
* Add Method-Override
