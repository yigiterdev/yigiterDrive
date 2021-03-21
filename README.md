# yigiterDrive

This project is a Google Drive Clone. I made this project to improve myself at React. This project includes React, Firebase, React-Router,Bootstrap. original version of the [Web Dev Simplified](https://www.youtube.com/watch?v=6XTRElVAZ9Y&list=LL&index=12&t=5328s&ab_channel=WebDevSimplified)

### You can look at original version of project made by [Web Dev Simplified](https://www.youtube.com/watch?v=6XTRElVAZ9Y&list=LL&index=12&t=5328s&ab_channel=WebDevSimplified)

## Live Demo

You can look at project demo in [here](https://yigiterdrive.vercel.app/login).

## Project setup

```
yarn install
```

### Compiles and hot-reloads for development

```
yarn serve
```

### Compiles and minifies for production

```
yarn build
```

### Setting Up Firebase

1. Set up a new project in Firebase with Database enabled.
2. Implement the following Firebase SDK scripts in firebase.js:

```
import firebase from "firebase";
firebase.initializeApp({
  apiKey: "",
  authDomain: "",
  databaseURL: "",
  projectId: "",
  storageBucket: "",
  messagingSenderId: "",
  appId: ""
});


```
