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

The MIT License (MIT)

Copyright (c) 2015 Rob Dodson

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
