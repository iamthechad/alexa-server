# Alexa Server Wrapper

This is a simple wrapper for the [`alexa-app-server`](https://github.com/matt-kruse/alexa-app-server) module to make development easier.

1. Install NodeJS version **4.x**
    * Follow any steps you wish to install - I prefer to use [NVM](https://github.com/creationix/nvm)
    * AWS uses NodeJS `4.3`, but any `4.x` version seems to work
1. Install required dependencies with `npm install`
1. Place your Alexa module(s) in the `apps` directory
1. Run `npm server.js` to start the server
1. Access your module at http://localhost:8080/alexa/your-module-name