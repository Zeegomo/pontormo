<p align="center">
  <img src="https://github.com/Zeegomo/pontormo/raw/master/images/pontormo.png"/>
</p>

## Requirements
* Docker

## Usage
* `docker build .`
* `docker run -it`

Running docker container will launch server in production.

Ctrl-C will close the server and save registered users to `out.csv`.

## Config

### Appearance
The `Config.toml` file is used to configure background color.

Pontormo will show the image at `assets/logo.png` in the footer, place here your logo if you want it to be displayed.

### Other
The `Rocket.toml` file is used to configure port, address and other server related options (see [Rocket](https://rocket.rs)).
