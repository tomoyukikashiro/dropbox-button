# &lt;pocket-button&gt;

Web Component wrapper for Pocket Button using Polymer

> Maintained by [kashiro](https://github.com/kashiro).

## Demo

> [Check it live](http://kashiro.github.io/pocket-button/index.html).

## Dependency

* [Polymer](http://www.polymer-project.org/)

## Browser Compatibility

Depend on Polymer's [Browser Compatibility](http://www.polymer-project.org/compatibility.html)

* 2013/09 : support modern browser exclude IE

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130905/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/pocket-button.html">
	```

3. Start using it!

	```html
	<pocket-button></pocket-button>
	```

## Options

Attribute  | Options                         | Default             | Description
---        | ---                             | ---                 | ---
`count`    | `none`, `horizontal`, `vertical`| `none`              |
`lang`     | `en` 	                     | `en`                |
`save-url` | *String*                        | `undefined`         | url to save
`align`    | `right`, `left`                 | `left`              | how the button will align inside of the button's iframe

more option [here](http://getpocket.com/publisher/button_docs)


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.1 September 23, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)
