# Elixre

[![Build Status](https://travis-ci.org/lpil/elixre.svg?branch=master)](https://travis-ci.org/lpil/elixre)
[![Code Climate](https://codeclimate.com/github/lpil/elixre/badges/gpa.svg)](https://codeclimate.com/github/lpil/elixre)

An Elixir regular expression editor & tester.

A massive rip off of Michael Lovitt's [Rubular](http://rubular.com/).

### Install it

You've got Erlang, Elixir, and Node installed, right?

```
mix deps.get
npm install
```

### Run it

```
mix phoenix.server
```

### Test it

```
mix test
grunt test
```

## Deployment

We're currently on Heroku, using these buildpacks.

* [ddollar/heroku-buildpack-multi](
    https://github.com/ddollar/heroku-buildpack-multi)
* [mbuchetics/heroku-buildpack-nodejs-grunt.git](
    https://github.com/mbuchetics/heroku-buildpack-nodejs-grunt.git)
* [HashNuke/heroku-buildpack-elixir](
    https://github.com/HashNuke/heroku-buildpack-elixir.git)

## LICENCE

```
Elixre - An Elixir regular expression editor & tester
Copyright © 2015 Louis Pilfold

This program  is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as
published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.
```
