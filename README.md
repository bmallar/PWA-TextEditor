# PWA-TextEditor

I made a PWA TextEditor to create notes or code snippets with or without an internet connection so that I can retrieve them for later use 

### Installation 
As a user everything will be downloaded because it is being deployed through render. As a creator I needed to download all of these dependencies 
  1. "devDependencies": {
   2.  "@babel/core": "^7.15.0",
   3. "@babel/plugin-proposal-object-rest-spread": "^7.20.7",
 4.    "@babel/plugin-transform-runtime": "^7.15.0",
  5.  "@babel/preset-env": "^7.15.0",
   6. "@babel/runtime": "^7.15.3",
   7. "babel-loader": "^8.2.2",
   8. "css-loader": "^6.2.0",
  9.  "html-webpack-plugin": "^5.3.2",
   10. "http-server": "^0.11.1",
  11.  "style-loader": "^3.2.1",
   12. "webpack": "^5.51.1",
   13. "webpack-cli": "^4.8.0",
   14. "webpack-dev-server": "^4.0.0",
  15.  "webpack-pwa-manifest": "^4.3.0",
  16.  "workbox-webpack-plugin": "^6.2.4"

### Usage 
This file is used to be ran offline (no internet connection needed) 

### Contributing 
I use a service worker and idb, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.





![Screenshot](./client/src/images/Screenshot%20(27).png)

1. [My repo Link](https://github.com/bmallar/PWA-TextEditor)
2. [My Live URL](https://pwa-texteditor-m4c4.onrender.com/)