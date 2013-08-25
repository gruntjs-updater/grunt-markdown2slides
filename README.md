# grunt-markdown2slides

Write your slideshow content in markdown without compromising stylability.

## Getting Started

This plugin requires Grunt `~0.4.1`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

### Usage

```sh
npm install grunt-markdown2slides --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-markdown2slides');
```

In your project's Gruntfile, add a section named `markdown2slides` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  markdown2slides: {
    files: {
      'dest/slides.html': ['src/slides.md'],
    },
  },
})
```