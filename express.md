1. `npm i express dotenv`
2. `npm i -D nodemon`
3. Add `"server": "nodemon server"` to package.json scripts
4. `npm run server` – app will crash 

server.js:

3. `console.log('hello world')` to test or 
  ```const express = require('express')
  const app = express()
  app.listen(3000)```
