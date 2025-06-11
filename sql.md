---
layout: page
permalink: /sql
title: "SQL"
subtitle: Simple mysql database model for managing events.
---
This project is a simple database model for managing events, featuring the following:
* Multiple and custom activity types (concerts, art expositions, musicals and so on)
* Multiple events of the same activity (is your concert sold out? schedule a new date for it)
* Automatically calculate the activity cost based on artists fee
* Manage venues
* Validate ticket sales based on venue capacity

The purpose of this work is to show case the process of modeling a database, from understanding the problem, down to the actual database implementation. While at the same time make use of important features of SQL, such as:
* Modeling (oltp)
* Insert, update, delete
* Triggers
* Views
* Basic queries (select, from, where, group by)
* Advanced queries (window functions)

**Note:** This is not intended to be a fully working, production ready database model.

The full project repository can be found here: [https://github.com/alvavr/sql](https://github.com/alvavr/sql)

![ER model](https://alvavr.github.io//img/er-diagram.png)

