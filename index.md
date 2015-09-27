---
layout: default
title: Introduction cloud-MES
---

## Welcome to use the next generation cloud MES

**Cloud-MES** is an Open Source, MES(Manufacturing Execution System) application for the factory. It is easy to integrate into existing applications using RESTful api, messenger queue or directly using database.

Cloud-MES is written in Ruby on Rails and can run quit well in Windows, Mac OS X and many Unix-like systems such as Linux and FreeBSD. Cloud-MES is also support many databse, including postgresql, mysql, Oracle or even MS SQL Server.

Cloud-MES is licensed under the [new BSD license](license.html).

### Features

- Modeling the factory using activerecord
- Modeling can support different kind of database
- All commen MES transaction include and can extend

{% for post in site.tags.news %}
---
<a href="{{ post.url }}">
<h3>{{ post.title }}</h3>
<span class="date">
<div class="dateday">{{ post.date | date: "%e" }}</div>
<div>{{ post.date | date: "%b" }}</div>
<div class="dateyear">{{ post.date | date: "%Y" }}</div>
</span>
</a>

{{ post.summary }}
{% endfor %}
<hr />

