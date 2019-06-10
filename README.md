# Source code for the [XAIR Manuals][] unofficial website

The website is built using [Jekyll][], using [Node.js][] to compile
all static assets including the [Bootstrap][] library and built on
along with the [SASS][] stylesheets. Most of the content on the website is
written using [Markdown][], making it extremely easy to write and maintain.
Icons are provided by [Font Awesome][], favicons by [Favicon Generator][].

[Bootstrap]: http://getbootstrap.com/
[Favicon Generator]: https://realfavicongenerator.net/
[Font Awesome]: http://fontawesome.io/
[Jekyll]: http://jekyllrb.com/
[Markdown]: https://daringfireball.net/projects/markdown/
[Node.js]: http://nodejs.org/
[SASS]: https://sass-lang.com/
[XAIR Manuals]: https://redtide.github.io/wiki-x-air

## Local Build Quick-start Guide

- Install `ruby` and `yarn`
- Use the automatic setup via `setup.sh`

or manually:

    $ gem update
    $ gem install bundler
    $ yarn --no-bin-links
    $ yarn dist
    $ bundle exec jekyll serve --watch --host 0.0.0.0

The local website should be available at <http://localhost:4000/>
