# &lt;mark-down&gt;
===================

> 

See the [component page](http://robdodson.github.io/mark-down) for more information.

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install robdodson/mark-down --save
```

Or [download as ZIP](https://github.com/robdodson/mark-down/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

```html
<script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="bower_components/mark-down/mark-down.html">
```

3. Start using it!

```html
<mark-down></mark-down>
```

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

```sh
$ [sudo] npm install -g bower grunt-cli
```

* Install local dependencies:

```sh
$ bower install && npm install
```

* To test your project, start the development server and open `http://localhost:8000`.

```sh
$ grunt server
```

* To provide a live demo, send everything to `gh-pages` branch.

```sh
$ grunt deploy
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Changes

For detailed changelog, check [Releases](https://github.com/robdodson/mark-down/releases).

## License

[MIT License](http://robdodson.mit-license.org/) © Rob Dodson
