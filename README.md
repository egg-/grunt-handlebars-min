# grunt-handlebars-min

>A grunt task for minifying and removing whitepace from [Handlebars](http://handlebarsjs.com/) templates.

## Getting Started

This plugin requires Grunt `~0.4.0`

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install https://github.com/moodyroto/grunt-handlebars-min.git --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks("grunt-handlebars-min");
```

## Handlebarsmin Task

_Run this task with the `grunt handlebarsmin` command._

### Usage

Use the `grunt-handlebarsmin` task by specifying a target source and a target destination and a destination extension.

```js
"handlebarsmin": {
    dist: {
        src: "./templates/handlebars/*.handlebars",
        dest: "./templates/min/",
        ext: ".handlebars"
    }
}
```

## Documentation

The `handlebars` task is a [multi task](https://github.com/gruntjs/grunt/blob/master/docs/types_of_tasks.md#multi-tasks), meaning that it will implicitly iterate over all of its targets if no target is specified.

## Contributing

Feel free to fork if you see possible improvements, or contact me directly if you want to contribute to this project (or just submit a pull request).d