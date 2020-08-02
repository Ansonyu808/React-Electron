# React and Electron App

Disclaimer: This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).  
[Electron Docs](https://www.electronjs.org/docs/tutorial/first-app#installing-electron)

### Description:

This app uses the popular web library: React in concurrence with Electron.  
This is useful because the official Electron docs only outline how to get basic html working.
Eventually, I plan to add flask as a backend and package the final application as an exe.

### How to run:

- Clone this repository
- `cd` into the repository
- Run `npm install` or `npm i` for short
- While editing the react files in the src folder (Hot reloading), run `npm start`
- To preview the desktop version (No hot reloading) Run `npm build` then `npm run start:desktop`

### How this was built:

- The idea was to package React into something Electron could run.
- I used `create-react-app`
- Then added Electron as a dev dependency
- Then created the Electron/app start point (main.js/electron.js) using the Electron docs.
- Finally I added the start point to the package.json and built the React files using `npm run build`
- Once the react file was built, interfacing Electron was the same as interfacing any html file with Electron (See the ocs)
