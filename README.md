# Pixel Punch

http://pixelpunch.voxmedia.com/

The event website for Vox Media's first design battle, Pixel Punch.

# Get running
The Pixel Punch website is built using the [jekyll](https://jekyllrb.com), the static site generator.

- Clone the project
- Run `bundle install`
- Run `bundle exec jekyll serve --livereload` to start up the server at `localhost:4000`
- Edit source files within the `source` folder

If you have SSL errors with `eventmachine`, install [Homebrew](http://brew.sh/) and then run `brew link --force openssl`, then try `bundle install` again.

To deploy:
- make sure you're on the `development` branch
- first build out files: `bundle exec middleman build`
- `bundle exec middleman deploy`
- source files will be outputted to `gh-pages` and update on pixelpunch.voxmedia.com.

## Authors
*2014* Development: Ngan Hoang, Ally Palanzi Design: Tyson Whiting, Katharine Molloy

*2015* Development: Ally Palanzi, Matt Sullivan Design: Katharine Molloy

*2016* Development: Marvin Cespedes Design: Jessica Paoli, Dani Balenson

*2017* Development: Marvin Cespedes Design: Katharine Molly, Irene Wang

## Contribute

This project is shared as-is. Bugs, issues, and pull requests may not be readily addressed.

## License

Copyright (c) 2014, Vox Media, Inc.
All rights reserved.

We're sharing this project in the hope that the methods and tactics here may be useful to others. That said, you may not republish this work. Learn from it and use it to build your own.
