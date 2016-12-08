[![Build Status](https://travis-ci.org/vaadin/vaadin-component-skeleton.svg?branch=master)](https://travis-ci.org/vaadin/vaadin-component-skeleton)

# &lt;vaadin-component-skeleton&gt;


## Running tests

```sh
npm test
```


## Contributing

1. Fork the <component-name> repository.

1. Make sure you have [npm](https://www.npmjs.com/) installed.

1. When in the <component-name> directory, run `npm install` to install dependencies.


## Running demos and tests in browser

1. Install [polyserve](https://www.npmjs.com/package/polyserve): `npm install -g polyserve`

1. When in the <component-name> directory, run `polyserve --open`, browser will automatically open the component API documentation.

1. You can also open demo or in-browser tests by adding **demo** or **test** to the URL, for example:

  - http://127.0.0.1:8080/components/vaadin-date-picker/demo
  - http://127.0.0.1:8080/components/vaadin-date-picker/test


## Running tests from the command License

1. Install [web-component-tester](https://www.npmjs.com/package/web-component-tester): `npm install -g web-component-tester`

1. When in the <component-name> directory, run `wct`, browser will automatically open the component API documentation.


## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. You can check if your code is following our standards by running `gulp lint`, which will automatically lint all `.js` files as well as JavaScript snippets inside `.html` files.


## License

Apache License 2.0

