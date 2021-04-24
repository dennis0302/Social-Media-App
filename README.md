# Social-Media-App

A simple social media app built with MongoDB, Express, React, Node.js and GraphQL.

Deployed on Heroku and Netlify.

# Usage

To run locally,

1. Install packages in root and client directory (Install Node.js if you don't already have one)

```
npm install
```

2. Create config.js in root directory and connect with MongoDB 

```
module.exports = {
    MONGODB: '<Enter your MongoDB connection string>',
    SECRET_KEY: '<Enter SECRET_KEY>'
};
```

3. Start server side in root directory

```
npm start
```

4. Start client side

```
cd client
npm start
```


5. http://localhost:3000/
