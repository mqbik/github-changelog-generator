# Dockerized GitHub Changelog Generator
[GitHub Changelog Generator](https://github.com/skywinder/github-changelog-generator) in Docker container.

## Generate the Changelog
Run the following command with your arguments.

```bash
$ docker run -it --rm -v $(pwd):/app mkubik/github-changelog-generator
```

## Why yet another Docker image

It is based on [ruby:2.4.1-alpine](https://hub.docker.com/_/ruby/) image to keep it small (84 MB).

It is beeing used every day at [AirHelp](https://www.airhelp.com) and I will update it if necessary.

## License

Dockerized Github Changelog Generator is released under the [MIT License](http://www.opensource.org/licenses/MIT).
