---
layout: post
title:      "Rack: Cheat Sheet"
date:       2017-12-26 18:58:54 +0000
permalink:  rack_cheat_sheet
---


What's Rack?

Rack is a Ruby gem that acts as a web framework, and adheres to a interface that can scale blocks of code to large applications.

Rack has three requirements for its template:

- A call method
- A "env" or "environment" argument for the call method
- A return function for status of HTTP

As long as your code fits those requirements, you can make an application that is connected to a server.

Since rails can break apart the 'layers' of an application, it makes it easier to manage code between rails and sinatra.
