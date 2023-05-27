---
layout: post
title: Ruby on Rails - Address Book
date: 2023-05-23 13:32:20 +0300
description: Ruby on Rails Project - Address Book. # Add post description (optional)
img: rails-1.png # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Ruby on Rails]
---

## Repo
[https://github.com/kiwiFella/RoR_addressBook_project](https://github.com/kiwiFella/RoR_addressBook_project)
 
## Overview
This project creates a simple address book app. 
The App shows a table of all the address entries, along with a single page to view each entry.
It uses basic user authentication to create private address book entries for each user_id.
Each user can only read, update & delete their own address book records.


## What I learnt during this project:
--------------------
- Installing ruby on a Mac
- Ruby `generate` functions to create:
    - controller, view, routes
    - `scaffolding` for database & corresponding CRUD function
    - migrating database
- Rails fundamentals regarding partials, routes, syntax
- Installing the `devise` gem package for user login/ logout access control.
- Create DB 'belongs_to' and 'has_many' `associations`.
- Manually updating database schema file and all other associated files to add a new field to a database, then migrate to database.
- Editing controller to add 
    - `before_action` logic 
    - created new function to prevent user editing other users data


## Screenshots

![I and My friends]({{site.baseurl}}/assets/img/rails-1/1.friends.png)
>Screenshot of the main table listing all the entries in the address book.

![I and My friends]({{site.baseurl}}/assets/img/rails-1/2.create.png)
>Screenshot of the form to create new entry.

![I and My friends]({{site.baseurl}}/assets/img/rails-1/3.created.png)
>Screenshot of the individual item page, plus showcasing the alert/notice messaging after successfully adding new person to address book.

![I and My friends]({{site.baseurl}}/assets/img/rails-1/4.sign-in.png)
>Screenshot showing secure sign-in form.

![I and My friends]({{site.baseurl}}/assets/img/rails-1/5.edit-profile.png)
>Screenshot of the form to manage users account.

![I and My friends]({{site.baseurl}}/assets/img/rails-1/6.sign-out.png)
>Screenshot showing sign out, redirect to index page and alert messaging .
