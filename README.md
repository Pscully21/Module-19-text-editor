# JATE(text-editor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
## Description
In this Homework for module 19 we were tasked with creating an application that helps us create notes/code-snippets that works offline, uses a service worker to help us cache items and uses an IndexedDB to create an object store with PUT and GET methods
## Table of Contents
- [Installation](#installation)
- [Built with](#built-with)
- [License](#license)
- [Screenshots](#screenshots)
- [Heroku link](https://honest-hippo.herokuapp.com/)

## Installation
1. To use this application yourself you can clone this repository by clicking on the green code button in the top-right of your screen, then copying the code and cloneing it using whatever coding software you use. 
2. The next step would require you to open the command line in the root of this repository and run ``` npm i ``` to install the dependencies required for this application to run
3. After this you can run ``` npm start ``` inside of your command line
4. When the above steps are completed you can open the browser and type in ``` localhost:3000 ``` which will bring you to the final application!

## Built with
- HTML
- CSS
- ExpressJS
- Javascript
- IndexDB
- Service Workers

## License 
This repo has the MIT license 

## Screenshots
The screenshots below are of the application itself and when looking in the application tab via inspect. I was able to get the indexedDB to work properly however, when changing some things around, Inspect now says I do not have a service worker. I have made one and saw it for a period of time however when I was trying to get the install function to work I changed some code in my ``` src-sw.js ``` file which ended up in the service worker not being recognized in the inspect window
./client/images/application.png
./client/images/inspect.png

## Heroku link
https://honest-hippo.herokuapp.com/
