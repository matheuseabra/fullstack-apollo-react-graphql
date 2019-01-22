# Rocket Apollo React GraphQL 

![Version](https://img.shields.io/badge/version-1.0-green.svg)

A fullstack app for reserving spots on the Space-X rocket using React with Apollo Client, GraphQL with Apollo Server and the Space-X API as data source.


## Quickstart

### Server

In the server root directory, run:

- npm install

Start the GraphQL playground:

- npm start

Open [http://localhost:4000](http://localhost:4000) to view it in the browser.

### Client

In the client root directory, run:

- npm install

Start the development server:

- npm start


Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Architecture

The app has five screens: a login screen, a list of launches, a launch detail, a profile page, and a cart. The graph API powering the app connects to a REST API and a SQLite database.

## Folder Structure

The folder structure of the project was built in the following manner:

- client
  - public 
  - src
    - assets
    - components
    - containers
    - pages
    - resolvers.js
    - styles.js
    - test-utils
    - index.js
  - apolllo-config.js

- server
  - src
    - schema.js
    - resolvers.js
    - utils.js
    - index.js
  - apolllo-config.js  
  - store.sqlite

## Author

This project was developed by Matheus Seabra.
- Website: http://matheuseabra.me
- Twitter: @matseabra