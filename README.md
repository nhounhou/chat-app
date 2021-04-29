# chat-app
chat application in React

# Table of Content
- [Installation](#installation)
- [React Modules](#react-modules)
- [Chat Deployment](#chat-deployment)
- [link](#link)
- [Improvements](#improvements)

# Installation
Once you clone the repo, run the following command to install all dependencies.
```
npm install
```

# React Modules
The Chat application is based on the folowing modules:
- chatengine.io, which is the web application that will manage the chat group/room and users
- React-chat-engine, is the react module to manage and render all the chat components. Here is the link to the [documentation](https://www.npmjs.com/package/react-chat-engine).

# Chat Deployment
The deployment was done thru netlify.com, very easy and simple way to deploy your application.
Here are the steps:
- In your VS Code application folder, run:
```
    npm run build
```
a `build` folder will be created
- Login to netlify
- Click on the `Sites` tab
- You will see a zone at the bottom of the page to drag and drop the `build` folder
![zone](./public/images/dargNdrop.jpg)
- And that's it, you can change the name of the app, and the deployment is done.

# link
[Chat App link](https://chat-app-unc.netlify.app)

# Improvements
At the moment, only the adminstrator can create group chat or rooms, and manage user credentials. this application was done within the developement of a final project during a Full Stack Web Developer BootCamp, here is the [link](https://bootcamp.unc.edu/).
- User management can be added.
- Messages management (delete, archive old messages, etc..).
- The entire UI is customizable as well, this can be added to be more user friendly.