# dependencies

Run `npm install`.

# start

In current setup, the _express server_ is serving both websocket backend and frontend assets (html, js, css). Webpack is used only to produce & watch files, there's no webpack-dev-server. 

## client compile

Run `npm run webpack`.

## ws server start

In order to start the server, which handles both real-time webservice and WWW server, run:

* `npm start` - standard mode
* `npm start -- -v` - verbose mode (prints each currency update on console)
* `npm start -- -p <PORT>` - custom port (default: 8080, http://localhost:8080)
