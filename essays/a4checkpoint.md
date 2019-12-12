---
layout: essay
type: essay
title: Assignment 4 Checkpoint
# All dates must be YYYY-MM-DD format!
date: 2019-12-11
labels:
  - Assignment 4
  - Checkpoint
---

## Describe the web-application you intend to build (in detail please!)
> The web app that my group intends to build is a store that will be used to service take-out orders and catering requests.

## Indicate how you expect the application will make use of the required technical complexity items (e.g. file I/O, sessions, multi-dimensional arrays, etc.)
> The web-app will make extensive use of mongoDB to read and write data regarding orders, catering requests, user accounts, etc. User passwords are salted and hashed using bcrypt. User authorization is being utilized through the use of json web tokens and localstorage. Forms are the medium used for interaction between the client and the database with the help of server validation to ensure only valid data is being used. Some of the pages that will be present is the products page which will present all available products and an admin panel that can be used to manage users, products, and catering requests.

## What is your plan to ensure you successfully complete your project before the end of the semester?
> Our plan is to meet throughout the week, including finals week if necessary to collaborate on the project. We already have mock up ideas about how most of the pages should look and function, however, we are still waiting on the final details regarding design choices.

## What progress have you made so far and what is left for you to do?
> Thus far, the project has functionality regarding user registration, user log in, user authorization, adding products to database, and user management. We still have to implement displaying all the products to the client and other product management, cart functionality, and catering requests.
