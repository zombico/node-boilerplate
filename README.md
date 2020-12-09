# Node Boilerplate

Served with Express 

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

This aims to be the bare minimum required to run a React app on a cloud server.

## Available Scripts

In the project directory, you can run:
### `cd app-name`
### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

--- note

Development mode consists of three things:  the server, the React app src, and the database.  

Running npm start will run both the server and React app in development mode.
A "proxy" object in the package.json lets you see your updates without running a build.


Build mode: 

In production, on the cloud, the React app also exists in a "Build" folder, which is like a zipped
or optimized file size that is the same thing as in your src.  A build command can be triggered on deployment.