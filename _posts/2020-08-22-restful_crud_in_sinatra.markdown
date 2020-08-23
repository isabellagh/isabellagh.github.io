---
layout: post
title:      "RESTful CRUD in Sinatra"
date:       2020-08-23 01:06:51 +0000
permalink:  restful_crud_in_sinatra
---

   I would like to start this blog by saying why I am writing about REST and CRUD. It is simply because I am still having a hard time understanding them. By the end of this blog, I am hoping to fully understand the mechanics of routes and transfers and everything that involves REST. So let's get started and dive into REST and CRUD.
   Wikipedia says that "Representational state transfer (REST) is a software architectural style that defines a set of constraints to be used for creating Web services."
   Roy Fielding is the great mind behind the scenes that came up with this new architectural style. In short, RESTful routes help developers and users to manipulate data in a simpler and more organized way, by matching HTTP verbs ( get, post, put, delete, patch ) also called "methods", to controller CRUD actions ( Create, Read, Update, Delete ). Create, Read, Update, and Delete are the four basic actions that models should be able to perform.
	 The implementation of codes on the server-side and the client-side is made separately, each does not need to know about the other, and their code changes do not interfere in each other's operations, as long as they follow the right format to exchange messages. The separation allows them to have more flexibility to improve themselves independently. In Sinatra, it corresponds to a method that we can use to build our route and match the HTTP verb.
	 
	 ![](http://1.bp.blogspot.com/-OYrCIhnLZSs/WDfolcFaWCI/AAAAAAAABdQ/3k787QiJFA4sdREpf_s54XgFMc7hM_E6QCLcB/s640/Client-Server_Rest.jpg!)
	 
	  As a stateless protocol, HTTP is not able to store any data, It treats every request as the first one, it does not remember the previous one. That being said, we must rely on each HTTP request. Where the website server sends information to the user's browser after received the request. That request is basically characterized by an HTTP verb, defining what kind of operation to perform and the resource. In terms of REST, the representation of the URI, in convention, the first piece of the path should be the plural form of the resource, as you will see in the examples below. Let's start with the fundamental elements of a persistent storage system in the REST environment. We can not talk about HTTP verbs without mentioning CRUD, which corresponds to the HTTP verbs/methods: POST (Create), GET (Read), PUT (Update), and DELETE (Delete/Destroy).
		
* 		  POST - Creates a new action. Whenever we render a form, our routes come in pairs. For example, after we GET the form (views), we use a POST request to create a new something and add it to the resource. (E.g. `post  "/dogs" ` means: create a new dog  [resource].)
		 
		 
* 		  Get -  The most used, which simply means: "GET or Read me the resource/path, please."
		    If the clients want to see something, an HTTP action of a GET request can be sent to the server, and it will be rendered to a view file or redirected to another URI. Reading a resource should never change any information, it only gets it. A Get request can read both static and dynamic routes, meaning one or more resources. (E.g. `get  "/dogs"` means: get me the page `"/dogs"`.)


* 		  PUT - This request can Update (by id) a piece of specific information in the database. (E.g. `put "/dogs/1"` means: update the attributes of the [resource] dog id of 1, with the given data.)


* 		  DELETE - is the HTTP method used to remove (by id) a resource from the system. (E.g. `delete  "/dogs/2"` means: delete the dog [resource] with the id 2.)
		 	 
	 
	  In the final analysis, I can say that writing this blog helped me very much in understanding the meaning of RESTfull routes and CRUD.  I wanted to thank Roy Fielding for creating this architectural style, it is very helpful for users to make requests and servers to send responses in a more organized way. In other words, in a RESTful interface, different clients will have the same REST final stage, all actions are the same as well as the responses received. When we think of HTTP verbs and CRUD to start the method in the controller it makes much more sense. Each verb/method corresponds to a CRUD action. It is good to remember them, POST (Create), GET (Read), PUT (Update), and DELETE (Delete/Destroy), those are not the only verbs, but for now, it is a good start. I am sure there is more than this to learn and write about this subject. This is my understanding so far and I will be more than happy to come back to this post to add and or fix wrong information that it may contain.
 






