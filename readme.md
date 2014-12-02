# middleman-haml-heroku

This is a Middleman HAML, SASS, production ready Heroku Boilerplate Template.

Creates a Middleman project with HAML templates, and is ready to push to Heroku. Runs on the following technologies:

* HAML for views
* Sass for stylesheets
* Coffeescript for javascript
* Puma server on Heroku

## Installation

Make sure the Middleman gem is installed

```bash
$ gem install middleman
```

Clone the repo and move it to the ~/.middleman (this is where Middleman looks for templates)

```bash
$ git clone git://github.com/austinlchang/middleman-haml-heroku.git
$ mkdir ~/.middleman
$ mv middleman-haml-heroku ~/.middleman/middleman-haml-heroku
```

## Getting started

To start a new Middleman project:

```bash
$ middleman init my-project --template=middleman-haml-heroku
```

Initialize the git repo:

```bash
$ git init
$ git add .
$ git commit -m "initial commit"
```

Create and push to Heroku:

```bash
$ heroku create
$ git push heroku master
$ heroku open
```

## License
Released under the [MIT License](http://www.opensource.org/licenses/mit-license.php). (c) 2014.
