# Calorie Counting App

A calorie counting app building using functional programming techniques.


### Installation

```
yarn install
```

### Start Dev Server

```
yarn start
```

### Build Prod Version

```
yarn run build
```

### Features:

* ES6 Support via [babel](https://babeljs.io/) (v7)
* SASS Support via [sass-loader](https://github.com/jtangelder/sass-loader)
* Linting via [eslint-loader](https://github.com/MoOx/eslint-loader)
* FP Style supported by [Ramda](https://ramdajs.com/)
* Hypertext created with JS courtsey of [HyperScript](https://github.com/hyperhype/hyperscript)

When you run `npm run build` we use the [mini-css-extract-plugin](https://github.com/webpack-contrib/mini-css-extract-plugin) to move the css to a separate file. The css file gets included in the head of the `index.html`.
