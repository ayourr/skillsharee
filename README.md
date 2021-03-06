# Skill Sharee API
NodeJS API for skill sharee App.

### Entities

1. User
2. post
3. post's comment
4. tag
5. page
6. events

### Getting Started
I use [babel Node](https://github.com/babel/example-node-server) for base of project. and [this tutorials](http://scottksmith.com/blog/2014/05/02/building.restful-apis.with-node) for create API.

try `npm install` after that `npm start` and enjoy! :smile:

### Tools and Technologies
- [Babel JS](Babel.io) : ES6❤️ compiler
- [Express](mongoosejs.com) : Node.js web application framework
- [npm](npmjs.com) : node package manager
- [Node.JS](nodejs.org) : Server side JS
- [Mongoose](mongoosejs.com) : elegant mongodb object modeling for node.js
- [Passport](passportjs.org/) : Passport is authentication middleware for Node.js
- [bcrypt-nodejs](https://www.npmjs.com/package/bcrypt-nodejs) : A native JS bcrypt library for NodeJS.(for hash and salt password)
- [express-restify-mongoose](https://florianholzapfel.github.io/express-restify-mongoose/) : Easily create a flexible REST interface for mongoose models

### Import/Export in MongoDB
[Back Up and Restore with MongoDB Tools](https://docs.mongodb.com/manual/tutorial/backup-and-restore-tools/)
Export (csv)
```
mongoexport --db skillsharee --collection users --type=csv --fields name,email,password --out /opt/backups/users.csv
```
Import (csv)
```
mongoimport --db skillsharee --collection users --type csv --headerline --file /opt/backups/users.csv
```
