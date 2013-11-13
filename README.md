# jQuery StickyNav

### A plugin to create sticky navigation


## Usage

1. Include jQuery:

	```html
	<script src="http://ajax.googleapis.com/ajax/libs/jquery/2.0.0/jquery.min.js"></script>
	```

2. Include plugin's code:

	```html
	<script src="dist/jquery.stickyNav.min.js"></script>
	```

3. Call the plugin:

	```javascript
	$("#element").stickyNav({
		propertyName: "a custom value"
	});
	```

## Structure

The basic structure of the project is given in the following way:

```
├── demo/
│   └── index.html
├── dist/
│   ├── jquery.stickyNav.js
│   └── jquery.stickyNav.min.js
├── src/
│   ├── jquery.stickyNav.coffee
│   └── jquery.stickyNav.js
├── .editorconfig
├── .gitignore
├── .jshintrc
├── .travis.yml
├── stickyNav.jquery.json
├── Gruntfile.js
└── package.json
```

#### [demo/](https://github.com/jquery-stickyNav/stickyNav/tree/master/demo)

Contains a simple HTML file to demonstrate your plugin.

#### [dist/](https://github.com/jquery-stickyNav/stickyNav/tree/master/dist)

This is where the generated files are stored once Grunt runs.

#### [src/](https://github.com/jquery-stickyNav/stickyNav/tree/master/src)

Contains the files responsible for your plugin, you can choose between JavaScript or CoffeeScript.

#### [.editorconfig](https://github.com/jquery-stickyNav/stickyNav/tree/master/.editorconfig)

This file is for unifying the coding style for different editors and IDEs.

> Check [editorconfig.org](http://editorconfig.org) if you haven't heard about this project yet.

#### [.gitignore](https://github.com/jquery-stickyNav/stickyNav/tree/master/.gitignore)

List of files that we don't want Git to track.

> Check this [Git Ignoring Files Guide](https://help.github.com/articles/ignoring-files) for more details.

#### [.jshintrc](https://github.com/jquery-stickyNav/stickyNav/tree/master/.jshintrc)

List of rules used by JSHint to detect errors and potential problems in JavaScript.

> Check [jshint.com](http://jshint.com/about/) if you haven't heard about this project yet.

#### [.travis.yml](https://github.com/jquery-stickyNav/stickyNav/tree/master/.travis.yml)

Definitions for continous integration using Travis.

> Check [travis-ci.org](http://about.travis-ci.org/) if you haven't heard about this project yet.

#### [stickyNav.jquery.json](https://github.com/jquery-stickyNav/stickyNav/tree/master/stickyNav.jquery.json)

Package manifest file used to publish plugins in jQuery Plugin Registry.

> Check this [Package Manifest Guide](http://plugins.jquery.com/docs/package-manifest/) for more details.

#### [Gruntfile.js](https://github.com/jquery-stickyNav/stickyNav/tree/master/Gruntfile.js)

Contains all automated tasks using Grunt.

> Check [gruntjs.com](http://gruntjs.com) if you haven't heard about this project yet.

#### [package.json](https://github.com/jquery-stickyNav/stickyNav/tree/master/package.json)

Specify all dependencies loaded via Node.JS.

> Check [NPM](https://npmjs.org/doc/json.html) for more details.


## Contributing

Check [CONTRIBUTING.md](https://github.com/jquery-stickyNav/stickyNav/blob/master/CONTRIBUTING.md)

## History

Check [Release](https://github.com/jquery-stickyNav/jquery-stickyNav/releases) list.

## License

[MIT License](http://zenorocha.mit-license.org/)
