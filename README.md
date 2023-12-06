# Basic JWT implementation. Please create .env with following variables. 
In order to manage users without a DB, in utils/users.js will be our own kind of user DB

```
id: process.env.USERNAME,
username: process.env.USERNAME,
password: process.env.PASSWORD,
fullname: process.env.FULLNAME,
secret: process.env.SECRET
PRIVATE_KEY_PATH:  process.env.PRIVATE_KEY_PATH
PUBLIC_KEY_PATH:process.env.PUBLIC_KEY_PATH
```
