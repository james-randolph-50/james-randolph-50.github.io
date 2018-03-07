---
layout: post
title:      "Authentication vs. Authorization"
date:       2018-03-07 22:08:15 +0000
permalink:  authentication_vs_authorization
---


AUTHENTICATION and AUTHORIZATION

Authentication and authorization are often confused, probably because they sound pretty similar and are frequently paired together (oops).

Authentication is determining who someone is. Banks do it with your PIN and a key stored in the chip of your card. TSA does it with your passport photo and their eyeballs.

Authorization is determining whether or not someone should have the ability to do something; such as bouncers authorizing you entrance to the club (except no one should say it like that).

AUTHENTICATION

Since handling your own login functions can be unsafe (unless you have a security background, it’s likely you’ll miss some low-hanging fruit for hackers), it’s common to use the Omniauth gem. The Omniauth gem allows you to leverage the OAuth protocol, which means that Google or Facebook can do the work for you.

The Devise gem also does this, it’s an open source authentication gem, and is loved as much as it’s hated.

AUTHORIZATION

Authorization deals with WHAT a user is allowed to do once we know WHO that user is.

So, remember which ones which to avoid confusion down the road.

