# The Grills Website

This is E-Commerce website for ordiering Grills Online. This website is built as a part of ALX Software Engineering course Backend Specialization. 


## App Feautres

1. User Authentication
2. DataBase Storage

## Demo

<div align="center">
    <img src="./readme_img/demo.gif" style="width: 640px" />
</div>


## Tech stacks used

1. React: To create the Single Page App.
2. React-Router: For Routing.
3. Redux: For State Management.
4. Firebase: As a DataBase.

## Firebase Setup

To start the app, you will need to create a firebase configeration file holding the firebase settings in the path `/src/firebase/config.js`. The required format is:

```javascript
const firebaseConfig = {
	apiKey: "API-KEY",
	authDomain: "AUTH-DOMAIN.firebaseapp.com",
	databaseURL: "DATABASE-URL.firebaseio.com",
	projectId: "PROJECT-ID",
	storageBucket: "STORAGE-BUCKET.appspot.com",
	messagingSenderId: "MESSAGING-SENDER-ID",
	appId: "APP-ID",
	measurementId: "MEASUREMENT-ID",
};

export default firebaseConfig;
```

## Steps to Use the App.

To use the project follow the steps given below:

1. Install the necessary modules (`npm install`).
2. Setup Firebase Project and configuration
3. Use `npm start` to run the react app

