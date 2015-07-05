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
<script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>
```

2. Import Custom Element:

```html
<link rel="import" href="bower_components/mark-down/mark-down.html">
```

3. Start using it!

```html
<mark-down>This is **awesome**</mark-down>
```

## Playing With Your Element

If you wish to work on the element in isolation, I recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep the bower dependencies
in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview the element at
`http://localhost:8080/components/mark-down/`.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://robdodson.mit-license.org/) © Rob Dodson
