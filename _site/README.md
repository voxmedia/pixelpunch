## Pixel Punch

A Vox Media AFK microsite

### Project

#### How to run

This microsite is based on [jekyll](https://jekyllrb.com) and is using [github pages](https://pages.github.com)

Please use the `master` branch to develop and use the `gh-pages` branch for releases.

To run the project change into the `pixelpunch` directory and do a `bundle install` wait for all the magic to happen and then run the command below and open [http://localhost:4000](http://localhost:4000)

```bundle exec jekyll serve --livereload```

-- enjoy

#### How it works

This is designed to be a single page app -- to add a new section add a new page in `_posts` and name it with the current date (things are ordered by date) ex. `2017-10-02-SOMENAME.markdown` while also adding head metadata

```
---
title: example
date: 2017-10-02 12:00:00
image: test.jpg
layout: page
---
```
