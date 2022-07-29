# Redux with React

## Project setup
##### Clone repository in your system:
```
git clone https://github.com/SterlingTrooTech/redux-form.git
```


##### Backend `to-do-task-be` setup:
Install `node_module` for backend
```
cd to-do-task-be
npm i
```

##### Connect with mongoDB:
If you already have connection in mongoDB, change `url` in `db.config.js` to connect to your database

redux-form/to-do-task-be/app/config/db.config.js:
```
module.exports = {
    url: `mongodb://localhost:27017`,
};
```

##### Start backend:
```
node server.js
```

##### Frontend `to-do-task` setup:
Install `node_module` for react-app
```
cd to-do-task
npm i
```

##### Start react-app:
```
npm start
```
