This is an example of RESTful CRUD in Node.js n mySQL.

Installation,Live DEMO, and tutorial here : http://teknosains.com/i/simple-crud-nodejs-mysql

## Installation

[![Greenkeeper badge](https://badges.greenkeeper.io/itranga/myapi.svg)](https://greenkeeper.io/)
*for newbies : Clone or download zip to your machine then hit this :

    cd rest-crud

then

    npm install

## Configuration (database)
server.js

        host: 'localhost',
        user: 'root',
        password : 'root',
        port : 3306, //port mysql
        database:'test'	


	
You're gonna need to create a DB named 'test' or whatever you name it,  import t_user.sql


## Open your Browser
And type: localhost:3000/api/user
