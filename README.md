# React

React is the library for web and native user interfaces. Build user interfaces out of individual pieces called components written in JavaScript. Check out their official documentation [here](https://react.dev/learn)

## Deploy a React App

In this tutorial, we have used create-react-app to setup our React project.

1. Fork/Clone this [React-Example](https://github.com/Hostless-Examples/React-Example) repo from github
2. Click on 'Create New App'
3. Choose a suitable app name
4. Choose you github account
5. Choose the forked github repo/the cloned remote repo
6. Choose a build system

    1. 'Detect automatically with Nixpicks' - automatically detects the programming language and builds the app
    2. 'Docker' - looks for a Dockerfile in the root of the project and build based on the instructions

7. Input a start command(optional) - By default uses ``yarn start``
8. The HOST environment variable is set by Hostless 

#### Sample configuration
![sample](https://res.cloudinary.com/do58rrxug/image/upload/v1713950264/Screenshot_2024-04-24_at_10.05.02_myteo8.png)

#### Example project
An example project is hosted on [https://hostless-react-cra.hostless.app/](https://hostless-react-cra.hostless.app/)

#### Note
- You may need to increase the memory of the app in the settings page. React app may not run with 128MB memory allocated to it.

