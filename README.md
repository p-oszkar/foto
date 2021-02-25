# Costiui

Costiui template for Jekyll. Browse through a [live demo](https://foto.costiui.ml/).

![Costiui template screenshot](https://foto.costiui.ml/media/screenshot.png)

## Setup

1. Add your site and author details in `_config.yml`.
2. Get a workflow going to see your site's output Jekyll locally).

## Develop

Costiui was built with [Jekyll](http://jekyllrb.com/) version 3.7.2, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

Aperture is already optimised for adding, updating and removing photos and navigation in Costiui.

### Navigation

* Exposed as a data file to give clients better access.
* Set in the *Data* / *Navigation* section.

### Photo Gallery

* Populated using front matter array in `index.html`.
