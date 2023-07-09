# Product Manager


<p align="center"> 
  <a href="https://www.linkedin.com/in/samuel-ricardo/" target="_blank">
    <img width="auto" src="https://cdn.webo.digital/uploads/2022/09/Nestjs_hero1.png"/>
  </a> 
</p>

<h4 align="center" > 🚀 🟥 Discovery 🟥 🚀 </h4>

<h4 align="center">
  Application developed with the purpose of studying the NestJS Ecosystem </a>
</h4>

#

<p align="center">
  |&nbsp;&nbsp;
  <a style="color: #8a4af3;" href="#project">Overview</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a style="color: #8a4af3;" href="#techs">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a style="color: #8a4af3;" href="#app">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;
  <a style="color: #8a4af3;" href="#routes">Routes</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a style="color: #8a4af3;" href="#run-project">Run</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;
  <a style="color: #8a4af3;" href="#author">Author</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

#

<br>

<p id="project"/>

<h2>  | :artificial_satellite: About:  </h2>

<p>
    This API is a tradicional CRUD that make the essentials operations like Create, Update and Delete Products that have relation with Category in MySQL database integrates using Prisma, all that using middlewares, Clean Architeture, Data Validations and more.
</p>

<br>

<h2 id="techs">
  :building_construction: | Technologies and Concepts Studied:
</h2>

> <a href='https://nestjs.com/'> <img width="48px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nestjs/nestjs-plain-wordmark.svg" /> </a>

- NestJS
- Prisma
- MySQL
- Typescript
- JS
- Test
- Jest  
- Docker
- eslint
- prettier
- husky
- class-validator
- class-tranformer
- lint-sataged

> Among Others...

<br>

#

<h2 id="app">
  💻 | Application:
</h2>


<p id="routes"/>


> API Example:

```bash
$ product_manager > api.http


### Category ###

###

GET http://localhost:3000/category

###

GET http://localhost:3000/category/1

###

POST http://localhost:3000/category
Content-Type: application/json

{
  "name": "Category 1i2"
}

###

PATCH http://localhost:3000/category/1
Content-Type: application/json

{
  "name": "Category 1 Updated"
}



###

DELETE http://localhost:3000/category/1

###



### Products ###


###

GET http://localhost:3000/products

###

GET http://localhost:3000/products/1

###

POST http://localhost:3000/products
Content-Type: application/json

{
  "name"  : "Product 1",
  "price" : 100,
  "categoryId": 1
}

###

PATCH http://localhost:3000/products/1
Content-Type: application/json

{
  "name"  : "Product 1 Updated",
  "price" : 50
}



###

DELETE http://localhost:3000/products/1

###


```
#

<br>

<h2 id="run-project"> 
   👨‍💻 | How to use
</h2>

<br>

### Open your Git Terminal and clone this repository

```git
  $ git clone "git@github.com:Samuel-Ricardo/product-manager_API.git"
```

### Make Pull

```git
  $ git pull "git@github.com:Samuel-Ricardo/product-manager_API.git"
```

<br>

This application use `Docker` so you dont need to install and cofigurate anything other than docker on your machine.

> <a target="_blank" href="https://www.docker.com/"> <img width="48px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-plain-wordmark.svg" /> </a>

<br>


Navigate to project folder ` $ cd ./product_manager/ ` and run it using ` docker-compose `


```bash

  # After setup docker environment just run this commmand on root project folder:

  $ docker-compose up --build   # For First Time run this command

  $ docker-compose up           # to run project


```

```bash

  #Apps Running on:

  $ API: http://localhost:3000
  $ MySQL: http://localhost:3306

  See more: ./product_manager/docker-compose.yaml

```

<br>

#

<br>

#

<h2 id="author">
  :octocat: | Author:  
</h2>
