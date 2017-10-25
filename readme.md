# @akameco/generator-nm [![Build Status](https://travis-ci.org/akameco/generator-nm.svg?branch=master)](https://travis-ci.org/akameco/generator-nm)

> Scaffold out a [node module](https://github.com/sindresorhus/node-module-boilerplate)

Optionally with a [CLI](http://en.wikipedia.org/wiki/Command-line_interface).

Fork from [sindresorhus/generator-nm](https://github.com/sindresorhus/generator-nm)


Diffs

- jest
- prettier
- flow
- eslint/eslint-config-precure
- hasky/lint-staged
- all-contirbutors

![](screenshot.png)


## Install

```
$ npm install --global yo @akameco/generator-nm
```


## Usage

With [yo](https://github.com/yeoman/yo):

```
$ yo nm
```

There are multiple command-line options available:

```
$ yo nm --help

  Usage:
    yo nm [options]

  Options:
    --help          # Print the generator's options and usage
    --skip-cache    # Do not remember prompt answers                      Default: false
    --skip-install  # Do not automatically install dependencies           Default: false
    --cli           # Add a CLI
    --coverage      # Add code coverage with nyc
    --coveralls     # Upload coverage to coveralls.io (implies --coverage)
```

## Tip

Use [chalk](https://github.com/sindresorhus/chalk) if you want colors in your CLI.


## License

MIT © [akameco](https://akameco.github.io)
