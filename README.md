# docker-capistrano-magentify

*Capistrano* based on Alpine.
Removed all unneeded content to keep it lightweight.

Build with Magentify.

## Workdir

/app

## Usage

Pull the image and connect to a host running a database!

Just run capistrano:

    docker run --rm -it -v `pwd`/.:/app srcoder/capistrano-magicento

Other tools which are added:

- magentify
- nokogiri
- json
- curb
- colored

## Authors

- [Jeroen Boersma](https://github.com/JeroenBoersma)

## License

MIT

