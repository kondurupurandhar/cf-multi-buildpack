# cf-multi-buildpack

Use multiple buildpacks on your app.

## Usage

Push your app with the argument `-b https://github.com/fuigo/cf-multi-buildpack.git`

    $ cat .cfbuildpacks
    https://github.com/heroku/heroku-buildpack-nodejs.git#0198c71daa8
    https://github.com/heroku/heroku-buildpack-ruby.git#v86

## License

MIT
