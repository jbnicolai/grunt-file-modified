# grunt-file-modified

> check if files is modified

## Getting Started
This plugin requires Grunt `~0.4.5`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-file-modified --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-file-modified');
```

## The "file_modified" task

### Overview
In your project's Gruntfile, add a section named `file_modified` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  file_modified: {
    your_task: {
      options: {
        output: 'tmp/config.json',
        files: [
          'path/to/**/*',
          '!path/to/ignore/file'
        ]
      }
    }
  },
});
```

### Options

#### options.output
Type: `String`
Default value: `'config/.grunt_file_modified'`

A file which marked down all files's MD5 hash.

#### options.files
Type: `Array`
Default value: `[]`

Files to be check.

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).

## Release History

- __0.0.1__ beta

