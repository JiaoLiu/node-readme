# node-readme ![npm](https://img.shields.io/npm/v/node-readme.svg) ![license](https://img.shields.io/npm/l/node-readme.svg) ![github-issues](https://img.shields.io/github/issues/revolunet/node-readme.svg)

Generate your JS project README.md using an ES6 template

![nodei.co](https://nodei.co/npm/node-readme.png?downloads=true&downloadRank=true&stars=true)

## Features

 - reads most of the data from package.json
 - list npm commands
 - author & licence
 - use a customizable ES6 template
 - badges

## Install

As a project dependency

`npm install --save-dev node-readme`

Or globally

`npm install --save-dev --global node-readme`

## Usage

Add a command in your package.json :

```json
"scripts": {
  "readme": "node-readme"
},
```

Then run `npm run readme` to generate your README.md.

You can copy and customize the [default README template](./src/.README.md) and add it to your project as `.README.md`.

It uses the [Javascript ES6 syntax](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/template_strings)

## Scripts  

 - **npm run readme** : `node bin/node-readme.js`
 - **npm run build** : `babel -d dist/ src/ && cp ./src/.README.md ./dist/.README.md`


## Author

Julien Bouquillon <julien@bouquillon.com> http://github.com/revolunet

## License

MIT : https://spdx.org/licenses/MIT.html
