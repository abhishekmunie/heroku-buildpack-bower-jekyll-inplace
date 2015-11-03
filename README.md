# Heroku Buildpack Bower - Jekyll

The Buildpack will look for a file named `_config.yml` and `bower.json` in the app root and
run first Bower then Jekyll to build the project.

A simple buildpack, designed to run with the [multi buildpack](https://github.com/ddollar/heroku-buildpack-multi),
which will run install bower and run `bower install`.

## Usage


```bash
$ ls
```
