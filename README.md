# Project: Item Catalog
By Gagan

## Technical Specifications

- Jquery
- Bootstrap v4.0 (alpha)

## What does this project

This project provides a list of items within a variety of categories as well as provide a user registration and authentication system.
Registered users will have the ability to post, edit and delete their own items.

## How to Run Project

* Clone `fullstack-nanodegree-vm` repository from 'https://github.com/udacity/fullstack-nanodegree-vm'.
* Replace contents of this folder from catalog folder in this repository (fullstack-nanodegree-vm).
* Go inside vagrant folder and run below command to launch vagrant
  - `vagrant up`
  - `vagrant ssh`
* Then go inside catalog folder by `cd /vagrant/catalog`
* Run below commands.
  - python database_setup.py (for databse setup)
  - python item_catalog.py (for insert some items with categories)
  - python application.py (to run application)

  Item catalog site will display into browser with `http://localhost:5000/`
