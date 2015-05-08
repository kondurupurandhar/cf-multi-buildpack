# cf-multi-buildpack

Use multiple buildpacks on your app.

## Usage

Push your app with the argument `-b https://github.com/fuigo/cf-multi-buildpack.git`

    $ cat .cfbuildpacks
    https://github.com/cloudfoundry/buildpack-ruby.git
    https://github.com/cloudfoundry/buildpack-nodejs.git

## License

MIT
