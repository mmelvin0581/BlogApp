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

<table style="width:100%">
    <tr>
        <td>index</td>
        <td>/dogs</td>
        <td>GET</td>
        <td>List all dogs</td>
    </tr>
    <tr>
        <td>new </td>
        <td>/dogs/new</td>
        <td>GET</td>
        <td>Show new dog form</td>
    </tr>
    <tr>
        <td>create</td>
        <td>/dogs</td>
        <td>POST</td>
        <td>Create a new dog, then redirect</td>
    </tr>
    <tr>
        <td>show</td>
        <td>/dogs/:id</td>
        <td>GET</td>
        <td>Show info about one dog</td>
    </tr>       
    <tr>
        <td>edit</td>
        <td>/dogs/:id/edit</td>
        <td>GET</td>
        <td>Show edit form for one dog</td>
    </tr>
    <tr>
        <td>update</td>
        <td>/dogs/:id</td>
        <td>PUT</td>
        <td>Update a particular, then redirect</td>
    </tr>
    <tr>
        <td>destroy</td>
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