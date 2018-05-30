# JavaScript Standalone Library Boilerplate
A simple Boilerplate to easily build JS Libraries with **Browserify**, **Watchify**, **Babel** and **UglifyJS** 

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Support](#support)
- [Contributing](#contributing)

## Installation

Download to your project directory, add `README.md`, and commit:

```sh
git clone https://github.com/jsrbn/js-library-boilerplate
```

## Usage

You can either _build_, _watch_ or _minify_ your library:

### Build:
```sh
# use this to build your library and to create a minified version of it at the same time

# using yarn
yarn build

# using npm
npm run build
```

### Minify:
```sh
# use this to minify the library.js file to library.min.js

# using yarn
yarn minify

# using npm
npm run minify
```

### Watch:
```sh
# use this to build your code every time you update it. Note: It won't be minified automatically

# using yarn
yarn watch

# using npm
npm run watch
```

## Support

Please [open an issue](https://github.com/jsrbn/js-library-boilerplate/issues/new) for support.

## Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and [open a pull request](https://github.com/jsrbn/js-library-boilerplate/compare/).