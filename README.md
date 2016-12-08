Heroku buildpack: MySQL
========================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for heroku, that installs and adds msyql (5.6) binaries to the $PATH on the dynos.

Usage
-----

Example usage:

    $ heroku buildpacks:add https://github.com/daetherius/heroku-buildpack-mysql
    $ git push heroku master

Based on [gaumire's work](https://github.com/gaumire/heroku-buildpack-mysql).
