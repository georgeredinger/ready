# ready
Run functions after the DOM is ready. A vanilla JavaScript alternative to jQuery's `.ready()` function.

[Download ready](https://github.com/cferdinandi/ready/archive/master.zip)


## Getting Started

### 1. Include ready on your site.

Include the code in your script, or load it as an external file.

```js
var ready = function ( fn ) {
	...
};
```

### 2. Run your code when the document is ready as a callback

```js
// Example
ready(function () {
	console.log( 'The document is ready.' );
});
```



## Browser Compatibility

ready works in all modern browsers, and IE 9 and above. You can test browser compatibility by checking for `addEventListener` support.

```js
if ( 'addEventListener' in window ) {
	// Your code...
}
```



## How to Contribute

Please review the [contributing guidelines](CONTRIBUTING.md).



## License

The code is available under the [MIT License](LICENSE.md).
