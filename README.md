## vuestacks-chat-mevn-okta-auth

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

![alt text](https://raw.githubusercontent.com/jsfanatik/vuestacks-chat-mevn-mongoose/master/src/assets/vuestacks-chat.JPG)

### Overview

The VueStacks chat MEVN demo utilizes Vue-Router, Axios HTTP client, Express server, and Mongoose.js to post messages in a chatroom. 

This demo utilizes Materialize CSS for general styling. See the CDN located in ```public/index.html```

See chat component in ```components/Chat.vue```

See login component in ```components/Home.vue```

See ```api/post.route.js``` to view Express router setup.

See ```api/post.model.js``` to view Mongoose schema setup.

### Setting Up Node/Express/MongoDB

1) Navigate to the folder “vuestacks-chat-mevn-mongoose/api” in the CLI
2) Run ```npm install```
3) Run ```nodemon server``` to start the server
4) In cloud.mongodb.com, retrieve the connection string for your MongoDB cluster
5) Add your connection string to ```DB = ''``` in ```api/DB.js```

### Setting Up Okta Authentication

1) Sign up for a forever-free developer account

![alt text](https://raw.githubusercontent.com/jsfanatik/vuestacks-chat-mevn-okta-auth/master/src/assets/okta-1.JPG)

2) Once logged in, create a new application by clicking “Add Application”.

![alt text](https://raw.githubusercontent.com/jsfanatik/vuestacks-chat-mevn-okta-auth/master/src/assets/okta-2.JPG)

3) Select the “Single-Page App” platform option.

![alt text](https://raw.githubusercontent.com/jsfanatik/vuestacks-chat-mevn-okta-auth/master/src/assets/okta-3.JPG)

4) The default application settings should be the same as those pictured.

![alt text](https://raw.githubusercontent.com/jsfanatik/vuestacks-chat-mevn-okta-auth/master/src/assets/okta-4.JPG)

Enjoy the demo! Submit an issue if you see anything that could be improved!
