# Prometheus Integration

## Prerequisites
     ### Local hosted
 - OS debian or ubuntu
 - [docker]
 - [docker-compose]()

## Project philosophy

The Cayman theme is intended to make it quick and easy for GitHub Pages users to create their first (or 100th) website. The theme should meet the vast majority of users' needs out of the box, erring on the side of simplicity rather than flexibility, and provide users the opportunity to opt-in to additional complexity if they have specific needs or wish to further customize their experience (such as adding custom CSS or modifying the default layout). It should also look great, but that goes without saying.

## Project structure

Layouts

## Install Docker-compose
```
docker-compose --version
```

in directories prometheus_inegration/installers/i run 

```
chmod +x install_compose.sh
execute ./install_compose.sh
```

## Docker-compose compatibility

First Check your docker version

```
docker --version
```

Here is the version compose file format 3.8 for Docker Engine release the 19.03.0+

If your version does not match with one provided,
you can change the version to the appropriate your one.

For full details on what each version includes and how to upgrade, see: [Compose and Docker compatibility matrix](https://docs.docker.com/compose/compose-file/)

## Roadmap

### Default Quic way VS Customizing way

If you'd like to add your own custom
Configuration variables

## Running tests
The theme contains a minimal test suite, to ensure a site with the theme would build successfully. To run the tests, simply run script/cibuild. You'll need to run script/bootstrap once before the test script will work.

## Contributing
Interested in contributing to Cayman? We'd love your help. Cayman is an open source project, built one contribution at a time by users like you. See the CONTRIBUTING file for instructions on how to contribute.


#prometheus #docker #docer-compose #debian:buster #nginx #apt-get #wget #yml