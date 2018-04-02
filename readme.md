[![Build Status](https://travis-ci.org/DimiMikadze/express-react-redux-starter.svg?branch=master)](https://travis-ci.org/DimiMikadze/express-react-redux-starter)
[![dependencies Status](https://david-dm.org/DimiMikadze/express-react-redux-starter/status.svg)](https://david-dm.org/DimiMikadze/express-react-redux-starter)

# Starter for Express, React, Redux, SCSS applications

## Features

- Webpack development and production environment configuration
- Webpack SCSS configuration
- React Hot loader
- React Router configuration
- React, Redux configuration
- Testing environment configured with Mocha and Chai
- Linting with Airbnb eslint configuration

## Getting Started

Clone Repo

````
git clone https://github.com/DimiMikadze/express-react-redux-starter.git
````

npm install dependencies

````
cd express-react-redux-starter 

npm install
````

### Start development server with hot reloading

````
npm run dev
````

### Testing

Run test once

````
npm run test
````

Test watch

````
npm run test:watch
````

### Linting

For linting i'm using Eslint with Airbnb Eslint configuration

````
npm run lint
````

### Production

Build for production

````
npm run build
````

Start production server

````
npm run start
````

Note: I'm using pm2 for production server, you should install it on server via 'npm install pm2 -g'.
if you don't want to use pm2, just change pm2 with node in package.json file in scripts section.

### Contributing

contributions are welcome!

### License

MIT
