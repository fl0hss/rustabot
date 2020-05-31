# Rustabot

This is a Rust bot for Discord servers. So far, I don't know if I will really focus on this project... Still, feel free to contribute !

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You will need the last version of Cargo and Rust

You also need to have your discord token as a variable environment

```
export DISCORD_TOKEN=<your discord token>
```

The dependencies for this project will be downloaded when you build the project

### Installing

A step by step series of examples that tell you how to get a development env running

For the stable version

```
git clone https://github.com/fl0hss/rustabot.git
cd rustabot
git checkout master
cargo build --release
./target/release/rustabot
```

For the development version

```
git clone https://github.com/fl0hss/rustabot.git
cd rustabot
cargo build
./target/debug/rustabot
```

To start the bot when you are developping 

```
cargo run
```

## Running the tests

TODO: No tests are available for now

### Break down into end to end tests

TODO: No tests are available for now

## Deployment

TODO: No deployment documentations are avaible for now

## Built With

* [Cargo](https://github.com/rust-lang/cargo) - The Rust dependencies manager

## Contributing

TODO: No contributing documentations are available for now

## Versioning

We use [SemVer](http://semver.org/) for versioning. 
TODO: No tags are configured right now 

## Authors

* **Fl0hss** - *Initial work* - [fl0hss](https://github.com/fl0hss)

## License

This project is licensed under the GNUv3 License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* This code is based on the [serenity-rs](https://github.com/serenity-rs/serenity) project, which provides Rust API for Discord