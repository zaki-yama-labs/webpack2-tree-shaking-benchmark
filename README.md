Webpack2 Tree Shaking Benchmark
===============================

A comparison of bundled module size between webpack 1.14.0 and 2.2.1 (with tree shaking).
[webpack-bundle-analyzer](https://github.com/th0r/webpack-bundle-analyzer) is used to visualize bundled module size.

## Installation

```zsh
$ npm install
```

## Usage


### To generate stats file


```
$ NODE_ENV=production ./node_modules/.bin/webpack --profile --json > stats.json
```


### To visualize bundled module

```
$ ./node_modules/.bin/webpack-bundle-analyzer stats.json
```

(Or you can also use https://chrisbateman.github.io/webpack-visualizer/)
