# JATE
Just Another Text Editor

## Table of Contents
- [JATE](#jate)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
  - [Installation](#installation)
  - [Features](#features)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [License](#license)
  - [Contact](#contact)

## About
This is a text editor web application that allows you to create and save notes or code snippets with or without an internet connection. It uses IndexedDB to store the notes locally and allows you to save them to the server when you are connected to the internet. It also allows you to delete notes from the server and locally.

## Installation
To install this application, you can clone the repository by running the following command in your terminal:
```
git clone
```
Then run the following command to install the necessary dependencies:
```
npm install
```
You can then run the application by running the following command:
```
npm start
```

## Features
* Uses IndexedDB to create an object store and includes both GET and PUT methods
* The application works without an internet connection
* Automatically saves content inside the text editor when the DOM window is unfocused
* Bundled with webpack
* Create a service worker with workbox that caches static assets
* The application should use babel in order to use async / await
* Application must have a generated manifest.json using the WebpackPwaManifest plug-in
* Can be installed as a Progressive Web Application   

## Usage
To use this application, simply navigate to the deployed application at https://jate-app31.herokuapp.com/. You can then create a new note by clicking the pencil icon in the top right corner. You can then save the note by clicking the save icon in the top right corner. You can delete a note by clicking the trash icon next to the note you want to delete. You can also delete all notes by clicking the trash icon in the top right corner.

## Contributing
If you would like to contribute to this project, please contact me at the email address below.

## License
MIT License [mit-license](https://opensource.org/licenses/MIT)

## Contact
Chad Ward
Email: chwdwile@aol.com
github: [chwd31](http;//github.com/chwd31)
