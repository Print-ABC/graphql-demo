# GraphQL Demo Web App 

This is a tutorial project I created to learn GraphQL. 

Link to video tutorial used can be found [here](https://youtu.be/ed8SzALpx1Q).

Link to course files can be found [here](https://github.com/iamshaunjp/graphql-playlist)

## Use Guide
You must have at least a basic **MongoDB Atlas** account to be able to run the project.

Go to `server/app.js` file and copy-paste your mongodb connection string (_and access credentials_) into the function at **line 14**.
> line 14 | mongoose.connect(_`<Paste string here>`_)

Afterwards, run the following commands from the root folder to start project: 
```
cd server
nodemon app
cd ../client
yarn start
```

