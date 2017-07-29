# Platzigram-db a module created with Platzi in the professional course Nodejs.

## Requirements:
* Rethinkdb.

## Before Install In Your Project.
You must create in Rethinkdb:
* One data base named `platzigram`
* Two `tables`, a named `images` and other named `users`

To `images table` You must create two index:
* `createdAt`
* `userId`

To `users table` You must create one index:
* `username`

## Install In Your Project:
```sh
  $ npm install --save git+https://isaacs@github.com/moisesdelacruz/platzigram-db.git
```

# Development

## installation:
```sh
  $ git clone https://github.com/moisesdelacruz/platzigram-db.git

  $ cd platzigram-db/

  $ npm install
```

## Test
```sh
  $ npm test
```
