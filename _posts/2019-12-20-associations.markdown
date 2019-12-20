---
layout: post
title:      "Associations"
date:       2019-12-20 19:07:38 +0000
permalink:  associations
---


Assoications are something we need to understand as developers. They define a relationship between classes of objects that allows one object instance to cause another to preform an action on its behalf. Associates are a set of macro-like class methods, they tie objects together through foreign keys. Each macro adds a number of methods to the models we defined. Depending on the macro we have defined, they get a certain collection of methods that will help us in the traversal and manipulation of its relationships. These associations can make our lifes much easier as developers and are very much so needed, for our classes that we define to understand their relationships or association between each other. There are some rules when creating associations like, we should not create one with the same name as instance methods. In doing so we can override the method inherited and can break things. There are many types of associations like, belongs_to, has_one, has_many, has_many :through, has_one :through, has_and_belongs_to_many. All of these different types of associations add different features to our models. For example using belongs_to, sets up a one-to-one relationship with another model. Associtations are an important use in creating our models and can make our models understand the connection between other models. Which then also gives us methods to use when developing our application.
