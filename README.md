# Middleman with Bower, jQuery, Bourbon, Neat & bitters

This is a template for [Middleman](http://middlemanapp.com) featuring:

* [Bower](http://bower.io/ "BOWER: A package manager for the web")
* [jQuery](http://jquery.com/ "jQuery")
* [haml](http://haml.info/ "Haml")
* [Sass](http://sass-lang.com "Sass: Syntactically Awesome Style Sheets")
* [Coffeescript](http://coffeescript.org/ "CoffeeScript")
* [normalize](https://github.com/necolas/normalize.css/ "normalize css")
* [Bourbon](http://bourbon.io "Bourbon - A Sass Mixin Library")
* [Neat](http://neat.bourbon.io "Bourbon Neat")
* [Bitter](http://bitters.bourbon.io "Scaffold styles, variables and structure for Bourbon projects")

## Installation

1. Download or clone this repository to:
  `git clone https://github.com/kwiss/middleman-bourbon-neat.git ~/.middleman/bower-bourbon-neat`
2. Create your new Middleman project with: `middleman init my_new_project --template=bower-bourbon-neat` use `--skip-bundle` if you install your bundle in vendor/ruby
3. `cd to_your_project_path`
4. Run `bundle install --path vendor/ruby`
5. Use `bower install` to install the assets in the `components/` directory (you'll need to have Bower npm package installed: `npm install -g bower`)
6. Run `bundle exec middleman`
