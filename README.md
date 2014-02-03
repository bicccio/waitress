# Waitress
An educational application done with NodeJS and AngularJS

## Layout
* **/** root directory with project automation stuffs and metadata
* **/api** server side
* **/frontend** client side
  * **/kitchen** front-end used in the kitchen
  * **/order-taker** front-end used on mobile devices by waiters
* **/test** front-end end-to-end tests

## Install
* install NodeJS ~= 0.10, I suggest you to use nvm
* install NodeJS needed global packages with `npm install -g yo grunt-cli bower karma phantomjs jshint`
  * if you have problems compiling binary packages you can try to run the following `npm install` commands specifying a python version that is >= v2.5.0 & < 3.0.0, like `PYTHON=python2.7 npm install`
  * set PHANTOMJS_BIN variable: ``export PHANTOMJS_BIN=`which phantomjs` ``
* install Ruby needed global packages with `gem install compass`
* install specific packages of components
  * `npm install`
  * `bower install`
  * `cd api; npm install; cd -`

## Run
* to run server `grunt server` and then `localhost:9000`
* to run unit tests `karma start`
* to run e2e tests `karma start karma-e2e.conf.js`

Every commands from /tools folder
