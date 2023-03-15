# XAIR Manuals (Unofficial Wiki)

Backup of old online wiki of Behringer X-Air manual,
converted to markdown for [Jekyll][1].

## Software

- [Jekyll][1] static site generator using [Markdown][2] content
- [Node.js][3] compiles static assets
- [Bootstrap v4][4] and [SASS][5] for stylesheets
- [Font Awesome][6] for icons
- [Favicon Generator][7] external site to create favicons

## Local Build Quick-start Guide

- Install `ruby` v2.7 and `yarn`
- Use the automatic setup via `setup.sh`

or manually:

```
$ gem update
$ gem install bundler
$ bundle install
$ yarn --no-bin-links
$ yarn dist
$ bundle exec jekyll serve --watch --host 0.0.0.0
```

The local website should be available at <http://localhost:4000/>


[1]: http://jekyllrb.com/
[2]: https://daringfireball.net/projects/markdown/
[3]: http://nodejs.org/
[4]: https://getbootstrap.com/docs/4.6/getting-started/introduction/
[5]: https://sass-lang.com/
[6]: http://fontawesome.io/
[7]: https://realfavicongenerator.net/
