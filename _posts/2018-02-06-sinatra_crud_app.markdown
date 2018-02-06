---
layout: post
title:      "Sinatra CRUD App"
date:       2018-02-06 23:23:32 +0000
permalink:  sinatra_crud_app
---

Building a CRUD (Create, Read, Update, Delete) app is mainly about the relationships between models. 

Mapping out exactly how users interact with the content (in this case, movies).

Like any project, programming or otherwise, I started by writing out the models and relationships that I intended to include in this app. From the get-go, I planned on users storing a collection of movies, each of which fall into a genre.

Therefore, I had the following:

- User have many movies
- a movie has one genre
- Users have many genres through movies

With that in mind, I had a clearer vision of how I needed my models to interact with one another.



