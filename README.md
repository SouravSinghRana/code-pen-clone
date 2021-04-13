# CodePen Clone

## What is the use of this Repo

This Project demonstrates the following
1. Creating a Component in React
2. Persisting data by using customHook
3. Communicating between parent and child component
4. Implementing ui similar to CodePen 

The project Template can be used to build bigger projects

## Live Application URL

### https://codepen-clone-12.netlify.app/
This URL has the application deployed in

## Prerequisites

### Install Node JS
Refer to https://nodejs.org/en/ to install nodejs

### Install create-react-app
Install create-react-app npm package globally. This will help to easily run the project and also build the source files easily. Use the following command to install create-react-app

```bash
npm install -g create-react-app
```
## Live Application URL

The Application is deployed in https://codepen-clone-12.netlify.app/

Click on the link to see the application

## Cloning and Running the Application in local

Clone the project into local

Install all the npm packages. Go into the project folder and type the following command to install all npm packages

```bash
npm install
```

In order to run the application Type the following command

```bash
npm start
```

The Application Runs on **localhost:3000**

## Application design

#### Components

1. **App** Component : This Component displays a list of editor and output area.

2. **Editor** Component : This Component Displays the editor for HTML CS and JS by using codemirror library. 

3. **useLocalStorage** customHook Component : This Component uses LocalStorage to persist data in the browser. 

#### HTTP client

**axios** library is used to make HTTP Calls


## Resources

**create-react-app** : The following link has all the commands that can be used with create-react-app
https://github.com/facebook/create-react-app

**ReactJS** : Refer to https://reactjs.org/ to understand the concepts of ReactJS
