
# EvolvBackendChallenge:pencil:


![Author](https://img.shields.io/badge/author-GovindCodes-green)
![License](https://img.shields.io/badge/license-MIT-brightgreen)
![Platform](https://img.shields.io/badge/platform-Visual%20Studio%20Code-blue)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555)](https://www.linkedin.com/in/govind-kumar-4ba162177/)
 
 ## Introduction:chocolate_bar:

Representational state transfer(REST) is web standards based architecture and uses HTTP Protocol. It revolves around resource where every component is a resource and a resource is accessed by a common interface using HTTP standard methods.:coffee::sweat_smile:

This **Blog App** is a web application developed on RESTful Routing using Node.JS, Express.JS, Embedded JavaScript (EJS) and more.:innocent::metal:

## RESTful Routes with Features:stars::stars:

:beginner:*Features of app is listed in purpose*:beginner:

| Name    | Path            | HTTP Verb | Purpose                                           | Mongoose Method          |
| ------- | --------------- | --------- | ------------------------------------------------- | ------------------------ |
| Index   | /blogs          | GET       | List all blogs                                    | Blog.find()              |
| New     | /blogs/new      | GET       | Show new blog form                                | N/A                      |
| Create  | /blogs          | POST      | Create a new blog, then redirect somewhere        | Blog.create()            |
| Show    | /blogs/:id      | GET       | Show info about one specific blog                 | Blog.findById()          |
| Edit    | /blogs/:id/edit | GET       | Show edit form for one blog                       | Blog.findById()          |
| Update  | /blogs/:id      | PUT       | Update a particular blog, then redirect somewhere | Blog.findByIdAndUpdate() |

similar for comments

## Files Description:eyeglasses:

* **app.js** is the main file that is the heart of our web application and contains the RESTful Routes defined for each event.
* **views** directory contains the relevant pages and parials, the EJS templates, that render on each event.
* **public/css** directory contains neccesary CSS used in web App
* **package.json** file contains the information towards the various dependencies and packages

## Run it locally:computer:

:camera::camera::camera::camera::camera::camera::camera:
*Start with Smile*:smile::smile:

1. Install [NodeJS](https://nodejs.org/en/):arrow_double_down:
2. Install [mongodb](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/):arrow_double_down:
3. Create a empty file and Open in your favourite code Editor.....shh...[VS Code Editor](https://code.visualstudio.com/download):wink:
4. Open the terminal window and write
```
git clone https://github.com/GovindCodes/RESTful-Blog-APP.git
```
This will files from repository to your local computer.:clock1::relieved::sun_with_face:

5. We need to install to necessary node modules, so use
```
npm install
```
6. Next thing to write on terminal is
```
node app.js
```
7.  **HURRAHHH**:boom: You completed all steps successfully go to [localhost:3000](http://localhost:3000/) on your browser and enjoy.


## What are the Benefits of NoSQL Databases?
NoSQL databases offer many benefits over relational databases. NoSQL databases have flexible data models, scale horizontally, have incredibly fast queries, and are easy for developers to work with.

* Flexible data models

NoSQL databases typically have very flexible schemas. A flexible schema allows you to easily make changes to your database as requirements change. You can iterate quickly and continuously integrate new application features to provide value to your users faster.

* Horizontal scaling

Most SQL databases require you to scale-up vertically (migrate to a larger, more expensive server) when you exceed the capacity requirements of your current server. Conversely, most NoSQL databases allow you to scale-out horizontally, meaning you can add cheaper, commodity servers whenever you need to.

* Fast queries

Queries in NoSQL databases can be faster than SQL databases. Why? Data in SQL databases is typically normalized, so queries for a single object or entity require you to join data from multiple tables. As your tables grow in size, the joins can become expensive. However, data in NoSQL databases is typically stored in a way that is optimized for queries. The rule of thumb when you use MongoDB is Data is that is accessed together should be stored together. Queries typically do not require joins, so the queries are very fast.

* Easy for developers

Some NoSQL databases like MongoDB map their data structures to those of popular programming languages. This mapping allows developers to store their data in the same way that they use it in their application code. While it may seem like a trivial advantage, this mapping can allow developers to write less code, leading to faster development time and fewer bugs.