## 19 Progressive Web Applications (PWA) : Text Editor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

The application is a web text editor where the user can create notes or code snippets with or without an internet connection and where the user can reliably retrieve them for later use.  The integrated service worker and Cache API's ensure that the application will remain fully functional even without and active internet connection.  This application allows the user to access visited pages even if the application is offline.

The URL of the GitHub repository is https://github.com/stellalph/19-PWA-Text-Editor.git and the repository name is 19-PWA-Text-Editor.

This application is deployed to Heroku and the URL of the deployed application is https://mighty-waters-80466.herokuapp.com/

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Deployment](#heroku)
* [References](#references)
* [License](#license)

## Installation

* This text editor require a number of methods and store data to an IndexedDB database to be builded up.

* This application will require the installation of Node.js and various npm packages.

*   Node Package Manager (npm) is a software manager and installer which puts the modules in place so that the node project can utilize it, and also, it manages dependency conflicts intelligently and initialized using **npm init**. The package.json will be generated and will contains all the details of the application in which the user have inputted during the npm initialization. 

*  This application will use the following npm packages:-

         * npm install express (express.js)
         * npm install --save-dev webpack (Webpack)
         * npm install webpack-dev-server --save-dev (webpack-dev-server)
         * npm install --save-dev webpack-pwa-manifest (WebpackPwaManifest)
         * npm install babel (Babel)
         * npm install --save-dev css-loader (CSS-loader)
         * npm install concurrently --save (run multiple commands concurrently.) (Concurrently)
         * npm npm install idb (IndexedDB)

* The required modules are bundled in the package.json file and at CLI or integrated terminal type in **npm run install**, the modules will be installed.       

## Usage

*   GIVEN a text editor web application, 
    WHEN I open my application in my editor
    THEN I should see a client server folder structure

*Below is the screenshot of the client server folder structure.  The folder structure have been set up or given in this structure.*

![alt text](/assets/images/TE07.png)


*   WHEN I run `npm run start` from the root directory
    THEN I find that my application should start up the backend and serve the client
    WHEN I run the text editor application from my terminal
    THEN I find that my JavaScript files have been bundled using webpack
    WHEN I run my webpack plugins
    THEN I find that I have a generated HTML file, service worker, and a manifest file

*Below are the screenshot of the running at npm run start, npm run build and also the generated HTML, service worker and a manifest file*

![alt text](/assets/TE02/images.png)
![alt text](/assets/TE08.png)


WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor

*Below is screenshot of the text editor "Just Another Text Editor (J.A.T.E)"*

![alt text](/assets/TE03.png)


THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB

*Below is screenshot of content in the text editor has been retrieved from the IndexedDB"*

![alt text](/assets/TE05.png)

WHEN I click on the Install button
THEN I download my web application as an icon on my desktop

*Below is screenshot of icon on the desktop"*

![alt text](/assets/TE04.png)

WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets



WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application 


## Deployment

The application has been deployed to Heroku.🚀
 
https://mighty-waters-80466.herokuapp.com/

## References



## License

This project is licensed under the terms of the MIT license.