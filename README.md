# Simple React app with Node server.

###### ( 5 minutes Hosting on Heroku - No configuration needed )

This is a simple React-Node starter pack which uses *React* for the client side and *Nodejs* for server.

*React App* was built using [create-react-app](https://github.com/facebook/create-react-app) boilerplate.

#### Start the development

~~~shell
git clone https://github.com/pankaja92/create-react-app-node.git
cd create-react-app-node
cd client && npm install
npm run build
cd ..
npm install
~~~

#### Deploy on Heroku

~~~shell
heroku create
git push heroku master
~~~

##### Server side Dependencies

* [express](https://expressjs.com/)
* [concurrently](https://www.npmjs.com/package/concurrently)
* [nodemon](https://www.npmjs.com/package/nodemon)

### Todo 

- [ ] Add Hot reloading on React App
- [ ] Add Auto Build on React App

#### This is not recommended from production as this project is still undergoing development and optimization

##

This example was build from the ideas from [Stephen Grider's Course](https://www.udemy.com/node-with-react-fullstack-web-development/) and with [this](https://github.com/mars/heroku-cra-node) project.
