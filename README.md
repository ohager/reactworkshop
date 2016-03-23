# [react-redux-starter-kit](https://github.com/cloudmu/react-redux-starter-kit)

Yet another React and Redux based web application starter kit. [Demo](http://ec2-52-10-209-45.us-west-2.compute.amazonaws.com/)

### Overview

This is a workshop project used for learning and teaching purposes.

## Credits

This project bases on [react-redux-starter-kit](https://github.com/cloudmu/react-redux-starter-kit). 
Thx for contribution!

### Install and Run the Dev Server (Linux/OSX)

```
npm install
npm run dev
```
Then open http://localhost:3000

### Build and Run the Production Server (Linux/OSX)

```
npm run build
npm start
```
Then open http://localhost
(Note the production port is set to 80 in package.json)

### Install and Run the Dev Server (Windows)

```
npm install
npm run dev-win
```
Then open http://localhost:3000

### Build and Run the Production Server (Windows)

```
npm run build-win
npm run start-win
```
Then open http://localhost
(Note the production port is set to 80 in package.json)

### Demo
A demo of this web application is running on a free [Amazon EC2 Micro Instance](http://ec2-52-10-209-45.us-west-2.compute.amazonaws.com/), with very limited resources.


### Feature highlights

* Best React practice by [separating "smart" and "dumb" components](https://medium.com/@dan_abramov/smart-and-dumb-components-7ca2f9a7c7d0)
* Async Data fetching with caching and pagination
* Data fetching error handling
* Authentication and Page Restrictions (based on JWT)
* Redirection upon logging in

### Dependencies

* React
* Redux
* React Router
* JSON Web Tokens (JWT)
* Fixed-Data-Table
* style-loader
* Bootstrap
* Express
* Babel
* Webpack
