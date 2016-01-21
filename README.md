# rzg-grunt-jasmine

Fork of the official [grunt-contrib-jasmine](https://github.com/tholewebgods/grunt-contrib-jasmine/tree/v0.5.3) package that [uses a fork of grunt-lib-phantomjs, called "rzg-grunt-lib-phantomjs"](https://github.com/tholewebgods/grunt-lib-phantomjs) that makes the PhantomJS binary configurable through an environment variable.

# Difference

Uses rzg-grunt-lib-phantomjs 0.7.2

# Usage

Since rzg-grunt-lib-phantomjs is not published you have to add both, this module and rzg-grunt-lib-phantomjs to your `package.json`

There are different ways installing it using npm 1, 2 and 3

## npm 1

```
devDependencies: {
    "rzg-grunt-lib-phantomjs": "0.7.2",
    "rzg-grunt-jasmine": "0.5.4",
}
```

and first

```
$ npm install path/to/rzg-grunt-lib-phantomjs
$ npm install path/to/rzg-grunt-jasmine
```

then

```
$ npm install
```

## npm 2

```
devDependencies: {
    "rzg-grunt-lib-phantomjs": "file:local/path/to/it",
    "rzg-grunt-jasmine": "file:local/path/to/it",
}
```

and first

```
$ npm install rzg-grunt-lib-phantomjs
$ npm install rzg-grunt-jasmine
```

then

```
$ npm install
```

## npm 3

```
devDependencies: {
    "rzg-grunt-lib-phantomjs": "file:local/path/to/it",
    "rzg-grunt-jasmine": "file:local/path/to/it",
}
```

and just

```
$ npm install
```

You need to set the environment `PHANTOMJS_BIN` pointing to the PhantomJS binary, see [rzg-grunt-jasmine](https://github.com/tholewebgods/grunt-contrib-jasmine).
