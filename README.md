# api_centric_weather_app
Made with: NodeJS, ExpressJS, AngularJS , Redis, Auth0

## Running Locally
make sure you have node and redis installed
to install redis use `$ brew install redis` or download from website
```
$ git clone git@github.com:konradgnat/api_centric_weather_app.git
$ cd api_centric_weather_app
$ npm install
$ redis-server
```
In a new terminal window cd into clone directory and start API server with `gulp`
Again in a new terminal window cd into clone directory
```
$ cd weather_client_browser
$ npm install
$ gulp
```

The app should now be running on localhost:3000 and the API on localhost:800
