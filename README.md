ES6 Playground
--------------

This is a simple ES6 playground repo that has barebone configuration for following libraries:

	* **browserify** : module system.
	* **babelify** : ES6 to ES5 transpiler
	* **grunt-contrib-connect** : development server.

To use, after cloning, `cd` to the project, do `npm install` and then in one termincal run `npm run dev` and in another terminal run `grunt connect`. Now open a browser and points to `http://localhost:9090`. Now make changes to `src/index.js` and refresh the browser to see your changes.