# cf-multi-buildpack

Use multiple buildpacks on your app.

## Usage

Push your app with the argument `-b <github clone url>`

    $ cat .cfbuildpacks
    https://github.com/cloudfoundry/buildpack-ruby.git
    https://github.com/cloudfoundry/buildpack-nodejs.git

## License

MIT
