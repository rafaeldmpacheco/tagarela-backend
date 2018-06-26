# Tagarela in NodeJS

## Main features

* User authentication

## Prerequisites

* [Node](https://nodejs.org) >= 6
* [MySQL](https://www.mysql.com/)

## How to run

### Database

1. Create database `use tagarela`
1. Insert document `db.user.insert({name: 'name', password: 'password', admin: true})`
1. Show documents `db.user.find()`

### Backend

1. `npm install`
1. `npm install -g gulp yarn nodemon`
1. `npm run build`
1. `npm start`
1. `npm run watch` for watch source changes

Runs on localhost:3000

Default system user/password: admin1/senha