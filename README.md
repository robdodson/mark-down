# &lt;mark-down&gt; & &lt;mark-down-editor&gt;

Web Component wrapper for Markdown using Polymer.

> Maintained by [Rob Dodson](https://github.com/robdodson).

## Demo

> [Check it live](http://robdodson.github.io/mark-down).

## Usage

1. Import Web Components' polyfill:

  ```html
  <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130905/polymer.min.js"></script>
  ```

2. Import [markdown-js](https://github.com/evilstreak/markdown-js):

  ```html
  <script src="lib/markdown.js"></script>
  ```

3. Import Custom Element:

  ```html
  <link rel="import" href="elements/mark-down.html">
  ```

4. Start using it!

  ```html
  <mark-down>Hello, **world!**</mark-down>

  <!-- or -->

  <mark-down-editor>Hello, **world!**</mark-down-editor>
  ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.1.0 October 02, 2013
  * Initial commit
* v0.2.1 October 03, 2013
  * Add mark-down-editor tag
* v0.2.2 October 07, 2013
  * Added text attribute so change handlers work
  * Added old and new syntax for styling host elements

## License

[MIT License](http://opensource.org/licenses/MIT)