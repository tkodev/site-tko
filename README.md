---
type: project
draft: false
date: '2017-01-19'
title: Site Base
topics:
  - code
  - gfx
tools:
  - hugo
  - node.js
  - gulp
  - sass
  - foundation
link: 'http://www.htko.ca'
code: 'https://github.com/htko89/htko-site-base'
photos:
  - cover.jpg
  - screenshot-ipadpro-landscape.jpg
  - mockup-surface.jpg
path: code/htko/site-base
---
# Personal Project
Hugo base for personal portfolio at htko.ca. An experiment in static site generation, using [HUGO](http://gohugo.io/) as the engine. Dynamic sites are heavy in resource usage are vulnerable to attacks. Static sites are fast, efficient and most of all, provide minimal avenues of attack. However, they are difficult to maintain, and do not scale well with large sets of data.

## Project Criteria:
* `gulp` task engine
* `gulp-sass`,`gulp-cssnano`,`gulp-autoprefixer` to compile scss files to css.
* `babel`,`gulp-concat`,`gulp-uglify` to compile js files.
* `gulp-sourcemaps` for sourcemapping.
* `globby`,`minimatch`,`fs-extra` for portfolio projects compilation.
* `js-beautify` for linting.
* `hugo` (`livereload`) or `browser-sync` for debug rendering.
