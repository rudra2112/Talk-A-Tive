<img src="client/public/logo512.png" height ="200px" align="right"/>

# Talk-A-Tive

A web-based chat application based on MERN Stack and Socket.io which features real time chat and notification functionality, and offering individuals features like one to one and group chats.

## Live Application URL

### https://talk-a-tive-xx7n.onrender.com

The application is hosted on Railway

## Prerequisites

### Install Node JS
Refer to https://nodejs.org/en/ to install nodejs

### Install create-react-app
Install create-react-app npm package globally. This will help to easily run the project and also build the source files easily. Use the following command to install create-react-app

```bash
npm install -g create-react-app
```

### Install nodemon
Install nodemon npm package globally. This will help to easily run the project and also build the source files easily. Use the following command to install nodemon

```bash
npm install -g nodemon
```

## Cloning and Running the Application in local

Clone the project into local

### Create Environment 
Create a file with name ".env" in the project folder and add the following variables

PORT = 5000
<br/>
MONGO_URI = (Your MongoDB URI)
<br/>
JWT_SECRET = (Your JWT Secret, It can be anything)

Install all the npm packages. Go into the project folder and Execute the following command to install all npm packages

```bash
npm install
```

Repeat the above process inside the client folder to install client side required packages

```bash
cd client
```

```bash
npm install
```

If you get an error, install all the packages from the client/package.json dependencies individually

```bash
npm install <package-name> --force
```

In order to run the application Execute the following command in project folder and in the client folder to start both the server and client side

```bash
npm start
```

The Application Runs on localhost:3000


### Production Build

For production build add the following line in the ".env" file
  
NODE_ENV = production

and execute the following command in the client folder

```bash
npm run build
```

## Resources

create-react-app : The following link has all the commands that can be used with create-react-app https://github.com/facebook/create-react-app

ReactJS : Refer to https://reactjs.org/ to understand the concepts of ReactJS
