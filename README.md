## What we did

* used a pre-made package.json file (has Babel, etc.)
* used a pre-made webpack.config.js file
* install webpack `npm install -g webpack`
* install webpack-dev-server `npm install -S webpack-dev-server`

#### Install Dependencies

`npm install`

#### Run Webpack Dev Server

`webpack --watch --content-base src --inline --hot`

This was added to our package.json file, so we can simply run `npm run dev`. Once we run this command, we can visit http://localhost:8080/ in our browser to view the app.
