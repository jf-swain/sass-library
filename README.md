[![Build Status](https://travis-ci.org/jf-swain/sass-library.svg?branch=master)](https://travis-ci.org/jf-swain/sass-library)
[![Codecov](https://codecov.io/gh/jf-swain/sass-library/branch/master/graph/badge.svg)](https://codecov.io/gh/jf-swain/sass-library)

# Sass Library


Library of sass function, mixin using theme/config files with map definition.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Sassdoc

A Sassdoc is created for this librairy, you could see it [here](http://sass-library.swain-creative.com/)

### Installing

Cloning the repo or download it

```
https://github.com/jf-swain/sass-library.git
```

Install dependencies:

```
yarn
```

### Running the tests

```
yarn test
```

### Checking the documentation

The instruction will create a sassdoc documentation and open it in your default browser

```
yarn docs
```
## Use this library

```
yarn add https://github.com/jf-swain/sass-library

```

How to use it :

* Import the `import.scss` file in front of your project in your scss file.


```
@import '[node_modules]/sass-library/import' || @import '~sass-library/import'
```


## Built With

* [SASS](https://sass-lang.com/) - The css preprocessor used
* [Jest](https://jestjs.io/) - The js test runner
* [True](http://oddbird.net/true/) - The test runner for sass
* [Sassdoc](http://sassdoc.com/) - The library to create sass documentation
* [Herman](https://github.com/oddbird/sassdoc-theme-herman) - the theme for sassdoc

## Authors

* **Jean-François Swain** - *Initial work* - [jf-swain](https://github.com/jf-swain)


## License

This project is licensed under the MIT License
