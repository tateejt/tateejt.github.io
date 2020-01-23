---
layout: post
title:      "Object Relationships"
date:       2020-01-23 03:21:19 +0000
permalink:  object_relationships
---

ActiveRecord Associations are a very important thing that we as developers need to understand. Associations are implemented using macro-style calls, so that you can add features to your models. For example declaring that one model has_many of another. You are telling rails to maintain Primary Key-Foreign Key information between instances of the two models. A has_many association indicates a one-to-many connection with another model. Often when using this association you find at the other end a belongs_to. In rails we use these associations to make life easier and simpliar in our code. For instance if we have a school model and a scholarship model. A school has_many scholarships and a scholarship belongs_to a school. These associations a key part of our code when building bigger projects so we can make many connections between our different models.
