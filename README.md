# Fastladder [![Build Status](https://travis-ci.org/fastladder/fastladder.png?branch=master)](https://travis-ci.org/fastladder/fastladder) [![Coverage Status](https://coveralls.io/repos/fastladder/fastladder/badge.png?branch=master)](https://coveralls.io/r/fastladder/fastladder) [![Code Climate](https://codeclimate.com/github/fastladder/fastladder.png)](https://codeclimate.com/github/fastladder/fastladder) [![Dependency Status](https://gemnasium.com/fastladder/fastladder.png)](https://gemnasium.com/fastladder/fastladder)

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

Fastladder (http://fastladder.com/) is the best solution for feed-hungry people who want to consume more RSS/Atom feeds, and this is its open-source version.
The open-source Fastladder, so called OpenFL, is an RSS reader to be installed on your PC or server with a capability to handle RSS feeds available within your Intranet.

## Setup

```
$ git clone git://github.com/fastladder/fastladder.git
$ cd fastladder
$ bundle install
$ bundle exec rake db:create db:migrate
$ bundle exec rake setup # Setup files for development
```

## Run

Run fastladder web process

```
$ bundle exec rails server
```

Run fastladder crawler process

```
$ bundle exec ruby script/crawler
```

You can run web and crawler processes by [foreman](https://github.com/ddollar/foreman).

```
$ foreman start         # run web and crawler processes
$ foreman start web     # run web process
$ foreman start crawler # run crawler process
```
