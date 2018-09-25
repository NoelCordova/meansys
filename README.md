# tweetclone

Maybe a Twitter clone made with mean stack technologies.

## Table of Contents
* [Checklist](#cheklist)
  * [Initial setup](#initial-setup)
  * [User - CRUD](#user---crud)
  * [To-Do](#to-do)


## Checklist
### Initial setup
* [x] Create an Angular project
* [x] Create a **server** and a **config** folder
  * [x] Create the _index.js_ for config
  * [x] Create _server.js_
* [x] Install node packages
  * _express_
  * _mongoose_
  * _cors_
  * _body-parser_
  * _bcrypt_
  * _joi_
* [x] Create the basics components on Angular
  * [x] home
  * [x] page-not-found
  * [x] api
* [x] Manage the routes on Angular
* [x] Make a reference of **dist** folder on server
* [x] Create a connection of mongodb with mongoose

### User - CRUD
* [ ] User routes
  * [x] Server API
  * [ ] Angular
* [ ] Create User
  * [ ] Create POST signup
    * [ ] Validate fields
    * [ ] Check if email is unique
    * [ ] Hash the password
    * [ ] Insert into DB
  * [ ] Login User
* [ ] Edit User
* [ ] Delete User

### To-Do
* [ ] Heroku repository
* [ ] Best way to manage routes, or this method is good??
* [ ] env variables
* [ ] Styles SCSS (I will try to not use bootstrap)... Ok, maybe just for the columns
