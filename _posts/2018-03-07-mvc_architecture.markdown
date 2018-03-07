---
layout: post
title:      "MVC Architecture"
date:       2018-03-07 22:04:22 +0000
permalink:  mvc_architecture
---


The MVC architectural pattern is composed of models, views, and controllers. MVC paradigm is a popular way to build frameworks for web apps because it adheres to the “separation of concerns” workflow.

So, instead of writing one enormous file with every single line of code for the web app in it, you can break the files down into models, views, and controllers (among other things) in order to make testing and debugging easier.

**Models**

The core element of MVC, models directly manage data, logic, and rules of the application. Think of the model as a chef in a restaurant - he decides what’s going on the menu, what alterations can be made on a dish, and so forth.

As the model is responsible for all things data, it responds to requests from the user AND controller in order to update itself.

**Controllers**

Controllers accepts inputs from the user (Yes, Netflix. I’m still watching this…) and converts it to commands for the model or view. If it’s easier, think of the controller as a waiter or waitress, who receives your order and sends it to the chef.

Controllers are made up of requests that are sent to the server. The built in methods include GET, POST, and DELETE - which perform the respective action on data.

Showing off your brunch on Instagram? You’re sending a POST request to the server. Taking down the post-bottomless mimosas selfie which didn’t turn out as expected? That’s sending a DELETE request to the server (hopefully before too many people saw it).

**Views**

Any output of information; charts, news-feeds, photos - anything. Again, going to the restaurant analogy, this could be the table, plate, or the food itself (if we're being fancy).

In Ruby, views are written with the file extension .erb, which contains HTML with embedded Ruby logic to dynamically change what the user sees.

Ruby code embedded in a web app is what makes the difference for things like the “login” button of the header change to “logout” depending on the user’s condition.

So, as a quick review:

Models are the brains; they manipulate and store data.

Views are the looks; it’s the only part users see and interact with.

Controllers are the middlemen; they carry data to and from models and views.

Just as a restaurant where employees were required to do a bit of everything wouldn’t be very efficient, one massive file of code is better off with the MVC structure. 

By putting the respective code in these types of files (separation of concerns), code is easier to read and write.
