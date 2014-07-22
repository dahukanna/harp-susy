# harp-susy

> Susy is a semantic CSS grid system with a responsive twist.

## Dependencies

* [Node.js](http://nodejs.org/) – _Server-side JavaScript runtime_
* [Harp](http://harpjs.com/) – _The static web server with built-in preprocessing_
* [Component](http://component.io) – _Client package management for building better web applications_

## Resources

* [Harp documentation](http://harpjs.com/docs)
* [Sass documentation](http://sass-lang.com/documentation/file.SASS_REFERENCE.html)
* [Compass documentation](http://compass-style.org/reference/compass/)
* [Susy documentation](http://susy.oddbird.net)
* [Susy tutorial](http://susy.oddbird.net/guides/getting-started/)

## Install

To install Susy, you can [download this repository](https://github.com/harp/susy/archive/master.zip) or use the [Component](http://component.io) package manager.

```bash
npm install -g component
component install harp/susy
```

[Compass Core](https://github.com/harp/compass) will also be installed, as Susy uses it. Your project will look something like this…

```
myproject/                  <-- Your project root (or public dir if in framework-mode)
  |- components/            <-- Harp puts Components here
  |   +- harp-compass/      <-- Where Compass is installed
  |   +- harp-susy/         <-- Where this lib is installed
  |       …
  |- main.scss              <-- Where you reference Compass Core and Susy 
  +- index.jade             <-- Where you reference main.css
```

## Link

Now, from within an `.scss` file in your project, you can `@import` Compass Core and Susy:

```scss
@import "components/harp-compass/scss/compass";
@import "components/harp-susy/scss/susy";
```

Or, simply import a portion of Compass:

```scss
@import "components/harp-compass/scss/css3";
```

## License

This component is [Susy](https://github.com/ericam/susy), which is Copyright © 2014 Eric Meyer.