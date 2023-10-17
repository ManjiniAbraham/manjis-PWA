# Note Taker
  
  [![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)]

## Description

The project is to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. The application will also function offline.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Credits](#credits)

## Installation

Install NodeJS. Also install all dependencies mentioned in the package.json files using the command 'npm install' in the terminal. 

## Usage

The app has been deployed on Heroku.

Live URL : 

Screenshots from Live site:

![Text Editor Home](/images/)

## License

License: [ISC License (ISC)](https://opensource.org/licenses/ISC)

[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)]


## Credits
https://webpack.js.org/guides/getting-started/


## Features

* Users can create and edit text-based notes both online and offline.
* Upon opening the application, users are presented with a client-server folder structure.
* Webpack plugins generate an HTML file, a service worker, and a manifest file.
* Content entered into the text editor is automatically saved in IndexedDB when users click off the DOM window.
* Upon reopening the text editor, previously saved content is retrieved from IndexedDB.
* Users can click on the "Install" button to download the web application as an icon on their desktop.
* The application registers a service worker using Workbox for offline capabilities.
* Static assets are pre-cached upon application loading, ensuring offline availability for both initial and subsequent pages.