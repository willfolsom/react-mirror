# React Mirror ![](public/mirror64.png)

### Create a React App and mirror it in a Chrome Extension.

This is a lightweight React App using Typescript, Webpack, and SASS that was bootstrapped with [Create React App](https://github.com/facebook/create-react-app). It can be used to develop a React App in the browser (or as a wrapper for ones that already exist), then to build it into a Chrome Extension, allowing the two to be developed upon in tandem.<br/>

![React Mirror](public/screeny.png)

### Run It

#### `npm i`

#### `npm start`

This runs the app in the development mode.<br/>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.<br/>
The page will reload if you make edits.

#### `npm run build`

Builds the app as a usable Chrome Extension to the **build** folder.<br/>
Navigate to **chrome://extensions** in Chrome, then click **Load unpacked** and select the base **build** folder.<br/>
After loading the extension, it can be debugged in the same way as the web app.

### et cetera

Noteworthy to checkout the manifest.json and background and content scripts. Plenty of literature out there. 😎
