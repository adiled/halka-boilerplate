# Project Structure

### index.js

Contains all javascript / npm / custom packages / global imports.
All the javascript code to be included must be included here for bundling.

### /web

Public directory

### web/src

All static assets are served from here. 

### web/src/scss

All `.scss` files go here.

### web/scss/main.scss

Main style file. All `.scss` must be imported into this for compilation.

### web/src/js

All custom js modules go here.

### web/src/bundle.js, web/src/main.css

Compiled files. Do not manipulate directly.

# How to setup

Use node.js version 8.9.4

- `npm install`
- `npm install browserify -g`

Start server

- `npm run start`
